#### Test 55431344148e3f8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/AndroidRuntime( 6369): 
D/AndroidRuntime( 6369): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6369): CheckJNI is OFF
D/AndroidRuntime( 6369): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  886): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6388 uid=10419 gids={50419, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6369): Shutting down VM
V/ActivityManager(  886): Display changed displayId=0
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6388): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
--------- beginning of crash
F/libc    ( 6369): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb4eb8010 in tid 6385 (Binder_1)
,I/LibraryLoader( 6388): Time to load native libraries: 2 ms (timestamps 7720-7722)
I/LibraryLoader( 6388): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6388): Binding Chromium to main looper Looper (main, tid 1) {2abb4d66}
I/LibraryLoader( 6388): Expected native library version number "",actual native library version number ""
E/DEBUG   (  291): unexpected waitpid response: n=6385, status=00000001
E/        (  291): ptrace detach from 6385 failed: No such process
E/        (  291): debuggerd committing suicide to free the zombie!
I/chromium( 6388): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/        ( 6408): debuggerd: Jan  6 2015 18:21:45
I/BrowserStartupController( 6388): Initializing chromium process, singleProcess=true
W/art     ( 6388): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6388): ApplicationContext is null in ApplicationStatus
W/chromium( 6388): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6388): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6388): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6388): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6388): Local Branch: 
I/Adreno-EGL( 6388): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6388): Local Patches: NONE
I/Adreno-EGL( 6388): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  886): Message: 20
D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a860455:true
W/ActivityManager(  886): Activity pause timeout for ActivityRecord{209af086 u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6388): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6388): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6388): CordovaWebView is running on device made by: motorola
W/art     ( 6388): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6388): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6388): Render dirty regions requested: true
D/Atlas   ( 6388): Validating map...
W/chromium( 6388): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6388): Initialized EGL, version 1.4
D/OpenGLRenderer( 6388): Enabling debug mode 0
I/Keyboard.Facilitator( 1424): onFinishInput()
I/LaunchCheckinHandler(  886): Displayed com.test.thalitest/.MainActivity,cp,ca,1007
I/ActivityManager(  886): Displayed com.test.thalitest/.MainActivity: +937ms (total +1s8ms)
W/IInputConnectionWrapper( 6388): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6388): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6388): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6388): Cannot call determinedVisibility() - never saw a connection for the pid: 6388
D/JsMessageQueue( 6388): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6388): JniHelper::setJavaVM(0xb8eb7310), pthread_self() = -1188801408
D/JX-Cordova( 6388): jxcore cordova android initializing
,W/art     ( 6388): Suspending all threads took: 8.300ms
,W/jxcore-log( 6388): Initializing JXcore engine
W/jxcore-log( 6388): JXcore engine is ready
,W/jxcore-log( 6388): Starting JXcore engine
I/art     ( 6388): Background sticky concurrent mark sweep GC freed 10916(1027KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 23MB/23MB, paused 10.468ms total 53.507ms
,W/.test.thalitest( 6388): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10419 path="socket:[9813]" dev="sockfs" ino=9813 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6388): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10419 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6388): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10419 path="socket:[7664]" dev="sockfs" ino=7664 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6388): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10419 path="socket:[29489]" dev="sockfs" ino=29489 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6388): Platform android
W/jxcore-log( 6388): 
,W/jxcore-log( 6388): Process ARCH arm
W/jxcore-log( 6388): 
,I/jxcore-log( 6388): JXcore Cordova bridge is ready!
I/jxcore-log( 6388): 
W/jxcore-log( 6388): JXcore engine is started
I/chromium( 6388): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/global frequency( 2623): no tags to log
,D/Checkin ( 2623): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2623): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1557): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/jxcore-log( 6388): Toggling radios to true
I/jxcore-log( 6388): 
,D/BluetoothAdapter( 6388): enable(): BT is already enabled..!
,D/WifiService(  886): New client listening to asynchronous messages
D/WifiService(  886): setWifiEnabled: true pid=6388, uid=10419
E/WifiService(  886): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6388): Radios toggled
I/jxcore-log( 6388): 
D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6388): Received device characteristics:
I/jxcore-log( 6388): Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6388): Bluetooth name: XT1072
I/jxcore-log( 6388): Device name: motorola-XT1072
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): Perf Test app loaded loaded
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): check test folder
I/jxcore-log( 6388): 
I/jxcore-log( 6388): found test : ./testFindPeers.js
I/jxcore-log( 6388): 
I/wpa_supplicant( 1440): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/Tethering(  886): InitialState.processMessage what=4
,I/wpa_supplicant( 1440): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  886): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  886): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
D/Tethering(  886):  0
,D/Tethering(  886): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1440): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1440): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
D/TCMD    (  483): Listening for incoming client connection request
V/NativeCrypto( 1758): Read error: ssl=0xb91c40a0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1758): SSL shutdown failed: ssl=0xb91c40a0: I/O error during system call, Broken pipe
,D/ConnectivityService(  886): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  886): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6451 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/jxcore-log( 6388): found test : ./testSendData.js
I/jxcore-log( 6388): 
,I/art     (  886): Explicit concurrent mark sweep GC freed 47888(2MB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 20MB/30MB, paused 2.145ms total 232.680ms
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiMetrics(  886): connected time updated 123738
,D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/wpa_supplicant( 1440): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  886): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/wpa_supplicant( 1440): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  886): ConnectModeState: Network connection lost 
E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1440): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  886): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  886): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  886): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Disconnected - quitting
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
,E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  886): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/chromium( 6388): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/ConnectivityService(  886): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  886): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     ( 2623): Explicit concurrent mark sweep GC freed 27361(1590KB) AllocSpace objects, 5(103KB) LOS objects, 39% free, 11MB/19MB, paused 1.035ms total 101.279ms
,D/BSUtils ( 2623): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2623): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2623): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1557): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/Babel_SMS( 6451): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6451): MmsConfig.loadMmsSettings
I/Babel_SMS( 6451): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6451): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6451): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6451): MmsConfig.loadFromResources
,E/Babel_SMS( 6451): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6451): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 56950(3MB) AllocSpace objects, 36(1226KB) LOS objects, 40% free, 7MB/12MB, paused 910us total 47.526ms
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
,D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  886): [1,452,246,572,081 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1440): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1440): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  886): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2cc868ba sup_state=SCANNING debouncing=false
,D/WifiMonitor(  886): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  886): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  886): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/BSUtils ( 2623): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2623): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2623): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1557): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/Settings( 6451): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6451): startup - clean
,I/Babel   ( 6451): deleted: false for 0
,D/TCMD    (  483): NL - Read 312 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 192 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1440): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/BSUtils ( 2623): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1440): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1440): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
,D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
,I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
,I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
,I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195680168
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Tethering(  886): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  886): Network connection established
,E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/BSUtils ( 2623): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/BSUtils ( 2623): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2623): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2623): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2623): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2623): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2623): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/ConnectivityService(  886): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  886): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Checkin ( 2623): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,E/WifiStateMachine(  886): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  886): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  886): Start Dhcp Watchdog 2
,I/global frequency( 2623): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2623): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  886): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6497 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  886): do suspend false
,E/wpa_supplicant( 1440): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  886): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1440): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e22b406 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e22b406 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6497): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6451): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6451): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6451): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Killing 6157:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/DHCPCD  ( 6514): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6514): version 5.5.6 starting
E/DHCPCD  ( 6514): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6514): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6514): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_6157/cgroup.procs: No such file or directory
,I/vclib   ( 6451): onServiceConnected
,W/Babel   ( 6451): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6514): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6514): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6514): wlan0: sending REQUEST (xid 0xbfadc22d), next in 4.94 seconds
,I/ActivityManager(  886): Killing 5981:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_5981/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6514): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6514): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6514): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6514): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6514): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6514): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 20
D/TCMD    (  483): Listening for incoming client connection request
D/DHCPCD  ( 6514): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,V/AlarmManager(  886): send {6e4b05d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  886): done {6e4b05d, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
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
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  886): Adding iface wlan0 to network 101
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  886): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  886): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  886): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  886): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  886): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  886): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  886): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886):    accepting network in place of null
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  886): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 09:49:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452246573101], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452246573085]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Validated
D/ConnectivityService(  886): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,D/ConnectivityService(  886): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
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
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2623): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6567 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1471): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2623): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2623): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2623): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2623): [debug] > CusSM.onRadioDown
,D/CCE     ( 2623): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2623): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2623): Registering with Alarm Manager to restart CCE
,I/art     (  886): Explicit concurrent mark sweep GC freed 40203(1999KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.898ms total 120.909ms
,I/MusicStore( 6567): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6567): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6567): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6567): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6567): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6567): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6567): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6567): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6567): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1110c262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6567): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6567): GMSCore installation verified
,I/ConfigStore( 6567): Config Database version: 1
,I/MediaRouter( 6567): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6567): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6567): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6567): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6616 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6567): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6567): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 6117:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10057/pid_6117/cgroup.procs: No such file or directory
,V/Mms     ( 6616): mnc/mcc: 
V/Mms     ( 6616): tag: int value: recipientLimit - 20
V/Mms     ( 6616): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6616): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6616): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6616): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6616): tag: bool value: enableGroupMms - false
,V/Mms     ( 6616):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6616): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6644 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 27.235ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.629ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.112ms
,I/ActivityManager(  886): Killing 6059:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6644): Register our PhoneStateListener
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_6059/cgroup.procs: No such file or directory
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  886): MasterInitialState.processMessage what=3
D/PollingManager( 2623): now: 198698 ,futureTime: 9223372036854775807
D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): now: 198699 ,futureTime: 9223372036854775807
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): now: 198700 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2623): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2623): [debug] > PollingManagerService, now: 198703 ,futureTime: 23094295
D/Central_PollingManager( 1471): now: 198704 ,futureTime: 86474057
,D/Central_PollingManager( 1471): Polling alarm set to expire at: 86474057 Current Time: 198704
D/OtaApp  ( 2623): [debug] > Polling alarm set to expire at: 23094295 Current Time: 198704
,D/OtaApp  ( 2623): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2623): [debug] > CusSM.onRadioUp
,I/NetworkMonitor( 6567): type=WIFI subType= reason=null isConnected=true
,D/MobileConnectivityChangeReceiver( 6644): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6644): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 2623): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2623): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2623): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2623): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2623): createDeviceIdOrLogin update_device
D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2623): Not proxy app, so login/provision not allowed
,I/ActivityManager(  886): Killing 6451:com.google.android.talk/u0a70 (adj 15): empty #7
D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2623): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2623): createDeviceIdOrLogin update_device
D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 4843(215KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 656us total 29.368ms
,D/MMApiProvisionService( 2623): set mOutstandingReq to true.
,I/ Nonce  ( 2623):  Nonce getNonce 
I/ Nonce  ( 2623):  Nonce Request 
I/ Nonce  ( 2623):  Nonce execute Request 
,D/MMApiWebService( 2623): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_6451/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2623): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2623): createDeviceIdOrLogin update_device
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2623): Not proxy app, so login/provision not allowed
,I/CheckinService( 6230): Checkin interval check for package: unspecified last checkin: 1452246492103 min interval config: 0 actual interval: 84088
,I/CheckinService( 6230): Disabling old GoogleServicesFramework version
,D/MMApiWebService( 2623): generating token using payload instead of using session token
,D/ Nonce  ( 2623):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2623): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinService( 6230): Checking schedule, now: 1452246576222 next: 1452246522081
I/CheckinService( 6230): active receiver: enabled
,I/iu.SyncManager( 6230): SYNC; picasa accounts
,D/NetworkLogImpl( 6230): Loaded NetworkSpeedPredictor
,I/CheckinService( 6230): Preparing to send checkin request
,I/iu.Environment( 6230): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6230): num queued entries: 0
,I/EventLogService( 6230): Accumulating logs since 1452246489123
,I/iu.UploadsManager( 6230): num updated entries: 0
,I/iu.SyncManager( 6230): NEXT; no task
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6683 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6230): Checkin reason type: 8 attempt count: 1
,D/WifiService(  886): New client listening to asynchronous messages
,E/ActivityThread( 6230): Failed to find provider info for com.google.android.wearable.settings
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6388): BLE is supported
I/jxcore-log( 6388): 
,I/art     (  886): Explicit concurrent mark sweep GC freed 9451(451KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.745ms total 118.607ms
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6706 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6706): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6726 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
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
,W/ResourcesManager( 6726): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6726): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6726): VM with version 2.1.0 has multidex support
I/MultiDex( 6726): install
I/MultiDex( 6726): VM has multidex support, MultiDex support library is disabled.
,I/Babel_SMS( 6706): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6706): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6706): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6706): MmsConfig.loadFromDatabase
,V/JNIHelp ( 6726): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel_SMS( 6706): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6706): MmsConfig.loadFromResources
,E/Babel_SMS( 6706): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6706): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 6726): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6726): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@323f649b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6726): Installed default security provider GmsCore_OpenSSL
,W/Settings( 6706): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6706): startup - clean
,I/art     ( 6726): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6726): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ Nonce  ( 2623):  Nonce Reponse 
D/        ( 2623): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7dd69100-39fa-479f-8063-964b84c688bf"}
D/MMApiWSBase( 2623): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/Babel   ( 6706): deleted: false for 0
,I/ Nonce  ( 2623):  Nonce Handle Reponse 
D/MMApiProvisionService( 2623): mOutstandingReq set to false
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6760 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6726): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,W/VideoCapabilities( 6706): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6706): Unsupported mime audio/amr-wb-plus
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55cc960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb89b8668, dataLength=8
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a43fc8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/VideoCapabilities( 6706): Unsupported mime video/mpeg2
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a8f7c0, idLength=0xbef0b2b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  295): PrepareKeyRequest: nonce=3090409333
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a35538
D/DrmWidevineDash(  295): message_length=1591, signature=0xb89252b0, signature_length=3203445396
,I/VideoCapabilities( 6706): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6706): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6706): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6706): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6706): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6706): onServiceConnected
W/Babel   ( 6706): Attempted to change video mute state without an active call.
,I/Babel   ( 6706): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  886): Killing 6497:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/DataUsage( 2623): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 2623): Explicit concurrent mark sweep GC freed 17948(1044KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/19MB, paused 18.738ms total 293.321ms
,D/MMApiProvisionService( 2623):  pTime 1452107623780 sExp 172742 cTime 1452246577648 tTime 1452280365780
D/MMApiProvisionService( 2623):  No login Required 
,W/libprocessgroup(  886): failed to open /acct/uid_10008/pid_6497/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6760): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6760): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6760): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6760): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6760):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6760):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6760): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6760): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6760): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6760): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6760): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6760): Time to load native libraries: 2 ms (timestamps 728-730)
,I/LibraryLoader( 6760): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6760): Binding Chromium to main looper Looper (main, tid 1) {337eaa8b}
I/LibraryLoader( 6760): Expected native library version number "",actual native library version number ""
I/chromium( 6760): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/dex2oat ( 6809): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/BrowserStartupController( 6760): Initializing chromium process, singleProcess=true
,W/art     ( 6760): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6760): ApplicationContext is null in ApplicationStatus
,W/chromium( 6760): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6760): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6760): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6760): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6760): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6760): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6760): Local Branch: 
I/Adreno-EGL( 6760): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6760): Local Patches: NONE
I/Adreno-EGL( 6760): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 6809): dex2oat took 98.484ms (threads: 4)
,I/Adreno-EGL( 6726): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6726): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6726): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6726): Local Branch: 
I/Adreno-EGL( 6726): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6726): Local Patches: NONE
I/Adreno-EGL( 6726): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6760): Requires BLUETOOTH permission
,I/NSApplication( 6760): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6834 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6567:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6726): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6726): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6726): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6726): Local Branch: 
I/Adreno-EGL( 6726): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6726): Local Patches: NONE
I/Adreno-EGL( 6726): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_6567/cgroup.procs: No such file or directory
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
,D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbef0b4e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb89c4368, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a43fc8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a8f800, idLength=0xb54cc730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  295): PrepareKeyRequest: nonce=3238785005
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89a5e30
,D/DrmWidevineDash(  295): message_length=1626, signature=0xb89ae988, signature_length=3041707796
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6858 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6616:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 6726): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6726): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6726): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6726): Local Branch: 
I/Adreno-EGL( 6726): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6726): Local Patches: NONE
I/Adreno-EGL( 6726): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_6616/cgroup.procs: No such file or directory
,W/ResourcesManager( 6858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6726): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6726): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6726): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6726): Local Branch: 
I/Adreno-EGL( 6726): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6726): Local Patches: NONE
I/Adreno-EGL( 6726): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6230): Classify the device as Phone.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6893 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6914 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6683:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 6893): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 6644:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_6683/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_6644/cgroup.procs: No such file or directory
,I/MusicStore( 6914): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6914): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6230): Sending checkin request (9453 bytes)
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6914): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6914): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6914): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6914): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6914): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6914): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1110c262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6914): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6914): GMSCore installation verified
,I/ConfigStore( 6914): Config Database version: 1
,I/art     ( 6198): Explicit concurrent mark sweep GC freed 1525(65KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 343us total 26.570ms
,I/MediaRouter( 6914): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6914): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6914): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6914): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6959 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6914): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6914): Using platform SSLCertificateSocketFactory
,I/art     (  886): Explicit concurrent mark sweep GC freed 11649(555KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.724ms total 114.735ms
,I/ActivityManager(  886): Killing 6706:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinRequestBuilder( 6230): Checkin reason type: 8 attempt count: 1
,V/Mms     ( 6959): mnc/mcc: 
,V/Mms     ( 6959): tag: int value: recipientLimit - 20
V/Mms     ( 6959): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6959): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6959): tag: int value: maxSubjectLength - 80
V/Mms     ( 6959): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6959): tag: bool value: enableGroupMms - false
,V/Mms     ( 6959):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf,
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_6706/cgroup.procs: No such file or directory
E/ActivityThread( 6230): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 6959): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6993 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6760:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 6993): Register our PhoneStateListener
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_6760/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6993): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6993): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6230): Checkin interval check for package: unspecified last checkin: 1452246492103 min interval config: 0 actual interval: 88091
,I/ActivityManager(  886): Killing 6834:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_6834/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6230): Classify the device as Phone.
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7015 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinTask( 6230): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6230): Checking schedule, now: 1452246580328 next: 1452847717318
I/CheckinService( 6230): active receiver: disabled
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 26.675ms
,I/CheckinService( 6230): Checking schedule, now: 1452246580353 next: 1452847717318
,I/CheckinService( 6230): active receiver: disabled
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.405ms
,D/CheckinService( 6230): Recording last checkin time for package unspecified as 1452246580356
,I/ActivityManager(  886): Killing 6893:android.process.acore/u0a7 (adj 13): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.332ms
,I/ActivityManager(  886): Killing 6858:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_6893/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_6858/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7041 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6914:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_6914/cgroup.procs: No such file or directory
,V/AlarmManager(  886): send {181e2df6, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/ResourcesManager( 7041): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7041): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7041): MmsConfig.loadMmsSettings
I/Babel_SMS( 7041): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7041): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7041): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7041): MmsConfig.loadFromResources
,E/Babel_SMS( 7041): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7041): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7041): startup - clean
,I/Babel   ( 7041): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7072 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7041): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7041): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7041): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7041): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7041): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7041): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7041): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7041): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7041): onServiceConnected
W/Babel   ( 7041): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 7072): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7072):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7072):   adb logcat -s GAv4
W/ContextImpl( 7072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7041): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7072): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  886): Killing 6959:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7072): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7072): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_6959/cgroup.procs: No such file or directory
,I/WebViewFactory( 7072): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7072): Time to load native libraries: 1 ms (timestamps 4373-4374)
I/LibraryLoader( 7072): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7072): Binding Chromium to main looper Looper (main, tid 1) {337eaa8b}
,I/LibraryLoader( 7072): Expected native library version number "",actual native library version number ""
I/chromium( 7072): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7072): Initializing chromium process, singleProcess=true
W/art     ( 7072): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7072): ApplicationContext is null in ApplicationStatus
,W/chromium( 7072): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7072): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7072): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7072): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7072): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7072): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7072): Local Branch: 
I/Adreno-EGL( 7072): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7072): Local Patches: NONE
I/Adreno-EGL( 7072): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7072): Requires BLUETOOTH permission
,I/NSApplication( 7072): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7145 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  886): Killing 6993:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_6993/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7164 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 7015:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7015/cgroup.procs: No such file or directory
,W/ResourcesManager( 7164): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7184 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7072:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7184): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 7041:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_7072/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7041/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2623): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2623): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2623): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2623): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2623): onServiceConnected()
,D/GetNotificationsWS( 2623): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2623): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2623): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7218 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7218): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7218): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7218): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7218): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1110c262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7218): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7218): GMSCore installation verified
,I/ConfigStore( 7218): Config Database version: 1
,I/MediaRouter( 7218): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/art     (  886): Explicit concurrent mark sweep GC freed 11668(602KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.631ms total 113.799ms
,V/MusicLeanback( 7218): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7218): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7218): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7254 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7218): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7218): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 7145:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7254): mnc/mcc: 
,V/Mms     ( 7254): tag: int value: recipientLimit - 20
V/Mms     ( 7254): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7254): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7254): tag: int value: maxSubjectLength - 80
V/Mms     ( 7254): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7254): tag: bool value: enableGroupMms - false
,V/Mms     ( 7254):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_7145/cgroup.procs: No such file or directory
,W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7284 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7164:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7164/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7284): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7284): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7284): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  886): Killing 7184:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7184/cgroup.procs: No such file or directory
,I/CheckinService( 6230): Checkin interval check for package: unspecified last checkin: 1452246580356 min interval config: 0 actual interval: 3367
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7307 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6230): Checking schedule, now: 1452246583803 next: 1452246610318
I/CheckinService( 6230): active receiver: disabled
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7324 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7218:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_7218/cgroup.procs: No such file or directory
,W/ResourcesManager( 7324): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7324): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7324): MmsConfig.loadMmsSettings
I/Babel_SMS( 7324): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7324): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7324): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7324): MmsConfig.loadFromResources
,E/Babel_SMS( 7324): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7324): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7324): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7324): startup - clean
,I/Babel   ( 7324): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7355 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.093ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 327us total 19.772ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.121ms
,W/VideoCapabilities( 7324): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7324): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7324): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7324): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7324): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7324): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7324): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7324): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7355): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7324): onServiceConnected
W/Babel   ( 7324): Attempted to change video mute state without an active call.
,I/GAv4    ( 7355): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7355):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7355):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7355): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7355): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 7355): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7355): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7355): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7355): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7324): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  886): Killing 7254:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_7254/cgroup.procs: No such file or directory
,I/WebViewFactory( 7355): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7355): Time to load native libraries: 1 ms (timestamps 7782-7783)
,I/LibraryLoader( 7355): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7355): Binding Chromium to main looper Looper (main, tid 1) {337eaa8b}
,I/LibraryLoader( 7355): Expected native library version number "",actual native library version number ""
,I/chromium( 7355): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7355): Initializing chromium process, singleProcess=true
,W/art     ( 7355): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7355): ApplicationContext is null in ApplicationStatus
,W/chromium( 7355): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7355): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7355): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7355): Local Branch: 
I/Adreno-EGL( 7355): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7355): Local Patches: NONE
I/Adreno-EGL( 7355): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7355): Requires BLUETOOTH permission
,I/NSApplication( 7355): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7427 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6726:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_6726/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7446 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 7284:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7284/cgroup.procs: No such file or directory
,W/ResourcesManager( 7446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7466 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7324:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7466): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 7307:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7324/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2623): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7307/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2623): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2623): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2623): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2623): onServiceConnected()
D/GetNotificationsWS( 2623): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2623): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2623): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2623): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2623): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2623): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  886): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7500 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2623): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2623): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2623): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2623): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2623): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2623): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2623): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2623): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6388): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1424): onFinishInput()
,I/LaunchCheckinHandler(  886): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,185
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1df2e010
,I/GCoreNlp( 1758): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1576): Deferring update until onResume
,I/art     (  886): Explicit concurrent mark sweep GC freed 18403(922KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.836ms total 150.446ms
,I/ActivityManager(  886): Killing 7355:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_7355/cgroup.procs: No such file or directory
,D/WearableService( 1758): callingUid 10016, callindPid: 1758
,D/LocationInitializer( 6230): Restart initialization of location
,D/AuthorizationBluetoothService( 1758): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1758): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,W/FusedLocationProvider( 1758): location=null
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7542 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7542): Register our PhoneStateListener
,V/SetupWizard( 7542): Connected to Gservices successfully
,V/AlarmManager(  886): done {181e2df6, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6440ms]
,D/GCM     ( 1758): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1758): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7567 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7594 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7611 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7427:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  886): Killing 7446:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_7427/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7446/cgroup.procs: No such file or directory
,W/ResourcesManager( 7611): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7611): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7611): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7611): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7611): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7611): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7611): MmsConfig.loadFromResources
,E/Babel_SMS( 7611): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7611): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7611): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7611): startup - clean
,I/Babel   ( 7611): deleted: false for 0
,W/VideoCapabilities( 7611): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7640 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7611): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7611): Unsupported mime video/mpeg2
,W/asset   ( 7640): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7640): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7640): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7640): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7611): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7611): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7611): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7611): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7611): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6230): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f430ec0 new=com.google.android.velvet.VelvetApplication@f430ec0
,I/UpdateIcingCorporaServi( 7567): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6230): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7671 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7611): onServiceConnected
,W/Babel   ( 7611): Attempted to change video mute state without an active call.
,I/Icing   ( 6230): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7611): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7611): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7671): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 7611): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/UpdateIcingCorporaServi( 7567): UpdateCorporaTask done [took 239 ms] updated apps [took 239 ms] 
,I/ActivityManager(  886): Killing 7542:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  ( 7611): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7611): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7542/cgroup.procs: No such file or directory
,I/art     ( 1758): Explicit concurrent mark sweep GC freed 104709(5MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 15MB/25MB, paused 1.202ms total 123.239ms
,E/DataBuffer( 1758): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1819608f)
E/DataBuffer( 1758): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3bd3df1c)
,E/DataBuffer( 1758): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32d8b725)
I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7706 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/DataBuffer( 1758): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39b170fa)
E/DataBuffer( 1758): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c5576ab)
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 21.109ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 18.911ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.424ms
,I/ActivityManager(  886): Killing 7500:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7500/cgroup.procs: No such file or directory
,D/Finsky  ( 7706): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TaskPersister(  886): removeObsoleteFile: deleting file=2_task.xml
,D/Finsky  ( 7706): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7706): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7706): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7706): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7706): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7706): Skipping gmscore version check
,I/ActivityManager(  886): Killing 7594:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_7594/cgroup.procs: No such file or directory
,D/Finsky  ( 7706): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7706): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6230): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6230): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6230): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  886): Killing 7640:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_7640/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7567:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_7567/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/CheckinService( 6230): Done disabling old GoogleServicesFramework version
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311077, SEQNUM=4474, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-332, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310630, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-356, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1758): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {4ba6918, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  886): send {308556b6, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  886): done {4ba6918, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  886): done {308556b6, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [30ms]
,I/CheckinService( 6230): Checkin interval check for package: unspecified last checkin: 1452246580356 min interval config: 0 actual interval: 46111
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/CheckinService( 6230): Checking schedule, now: 1452246626491 next: 1452246610318
I/CheckinService( 6230): active receiver: enabled
,I/CheckinService( 6230): Preparing to send checkin request
I/EventLogService( 6230): Accumulating logs since 1452246576388
,I/CheckinRequestBuilder( 6230): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6230): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  886): Explicit concurrent mark sweep GC freed 15841(804KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.347ms total 114.479ms
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7789 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7789): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7789): VM with version 2.1.0 has multidex support
I/MultiDex( 7789): install
I/MultiDex( 7789): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7789): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7789): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7789): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@323f649b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7789): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1758): callingUid 10016, callindPid: 1758
,E/MDM     ( 1758): [218] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6230): Restart initialization of location
,D/AuthorizationBluetoothService( 1758): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7789): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7789): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/GCoreFlp( 1758): No location to return for getLastLocation()
W/FusedLocationProvider( 1758): location=null
,D/NativeLibraryUtils( 7789): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbef0b4e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb89bb370, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a43fc8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a8f7e0, idLength=0xb54cc730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1870939890
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a35538
D/DrmWidevineDash(  295): message_length=1591, signature=0xb89ae988, signature_length=3041707796
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7832): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7832): dex2oat took 60.542ms (threads: 4)
,I/Adreno-EGL( 7789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7789): Local Branch: 
I/Adreno-EGL( 7789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7789): Local Patches: NONE
I/Adreno-EGL( 7789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7789): Local Branch: 
I/Adreno-EGL( 7789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7789): Local Patches: NONE
I/Adreno-EGL( 7789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbef0b4e0
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb89bb560, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a43fc8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a8f800, idLength=0xb55cc730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=131281538
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89a5e30
D/DrmWidevineDash(  295): message_length=1625, signature=0xb89ae988, signature_length=3042756372
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7789): Local Branch: 
I/Adreno-EGL( 7789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7789): Local Patches: NONE
I/Adreno-EGL( 7789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7789): Local Branch: 
I/Adreno-EGL( 7789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7789): Local Patches: NONE
I/Adreno-EGL( 7789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6230): Classify the device as Phone.
,I/CheckinTask( 6230): Sending checkin request (9443 bytes)
,I/CheckinRequestBuilder( 6230): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6230): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6230): Classify the device as Phone.
,I/CheckinTask( 6230): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6230): Checking schedule, now: 1452246630430 next: 1452847767420
I/CheckinService( 6230): active receiver: disabled
,D/CheckinService( 6230): Recording last checkin time for package unspecified as 1452246630451
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7863 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7863): Register our PhoneStateListener
,V/SetupWizard( 7863): Connected to Gservices successfully
,D/GCM     ( 1758): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  886): Killing 7671:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  886): Killing 7466:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7671/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7466/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7894 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@73d8826
,I/GCoreNlp( 1758): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7926 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7948 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7706:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_7706/cgroup.procs: No such file or directory
,W/ResourcesManager( 7611): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7611): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 7948): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7980 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7863:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7863/cgroup.procs: No such file or directory
,W/asset   ( 7980): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7980): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6230): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6230): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7894): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f430ec0 new=com.google.android.velvet.VelvetApplication@f430ec0
,I/Icing   ( 6230): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8007 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7894): UpdateCorporaTask done [took 148 ms] updated apps [took 147 ms] 
,I/art     (  886): Explicit concurrent mark sweep GC freed 18140(944KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.552ms total 115.180ms
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8035 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7789:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_7789/cgroup.procs: No such file or directory
,D/Finsky  ( 8035): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8035): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8035): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8035): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8035): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8035): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8035): Skipping gmscore version check
,D/Finsky  ( 8035): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8035): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  886): Killing 7926:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_7926/cgroup.procs: No such file or directory
,I/Icing   ( 6230): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6230): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  886): Killing 7980:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_7980/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7611:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7611/cgroup.procs: No such file or directory
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1424): run()
,I/Keyboard.Facilitator( 1424): flushDynamicLanguageModels()
,I/ConfigService( 1758): onCreate
,I/ConfigService( 1758): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312033, SEQNUM=4500, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-428, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6388): Connected to the server!
I/jxcore-log( 6388): 
,I/chromium( 6388): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
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
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311653, SEQNUM=4502, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-626, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6388): --- start :testFindPeers.js---
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): testFindPeers created [object Object]
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): serverPort is 8876
I/jxcore-log( 6388): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6388): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6388): bind: Binding a new listener
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6388): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6388): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6388): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6388): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6388): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6388): start: OK
I/io.jxcore.node.ConnectionHelper( 6388): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6388): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6388): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6388): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6388): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  886): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState add service
,D/WifiP2pService(  886): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): start: Starting P2P device discovery...
,D/WifiP2pService(  886): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  886): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6388): start: OK
,I/jxcore-log( 6388): StartBroadcasting started ok
I/jxcore-log( 6388): 
,I/chromium( 6388): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6388): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6388): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6388): onDiscoveryManagerStateChanged: RUNNING
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  886):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  886):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService(  886): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState add service request
,D/WifiP2pManager( 6388): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service request added successfully
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1440): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  886): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  886):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  886):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): InactiveState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/WifiP2pService(  886): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState discover services
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service discovery started successfully
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
I/wpa_supplicant( 1440): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
I/wpa_supplicant( 1440): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  886): InactiveState{ when=-2ms what=147477 obj=Device: A5-1
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): InactiveState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):,  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  886): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6388): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 6388): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 6388): 
I/jxcore-log( 6388): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 6388): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  886): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6388): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 6388): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 6388): 
I/jxcore-log( 6388): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6388): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: RESTARTING
,D/WifiP2pService(  886): InactiveState{ when=0 what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1440): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/WifiP2pService(  886): InactiveState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): discovery change broadcast false
,D/WifiP2pService(  886): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  886): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): Start timer timeout, starting now...
,D/WifiP2pService(  886): InactiveState{ when=0 what=139265 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139265 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  886): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  886): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): restart: Restarting...
,D/WifiP2pService(  886): InactiveState{ when=0 what=139307 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139307 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState clear service request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139301 arg2=23 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139301 arg2=23 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState add service request
,D/WifiP2pManager( 6388): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service request added successfully
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139310 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139310 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState discover services
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service discovery started successfully
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  886): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  886): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6388): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  886): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6388): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 6388): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6388): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 7e
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 7e
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: RESTARTING
,D/WifiP2pService(  886): InactiveState{ when=0 what=139268 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1440): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1440): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/WifiP2pService(  886): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): discovery change broadcast false
,D/WifiP2pService(  886): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: null
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 0
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 0
D/WifiP2pService(  886):  status: 4
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): Start timer timeout, starting now...
,D/WifiP2pService(  886): InactiveState{ when=0 what=139265 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139265 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  886): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): restart: Restarting...
,D/WifiP2pService(  886): InactiveState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState clear service request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139301 arg2=34 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139301 arg2=34 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState add service request
,D/WifiP2pManager( 6388): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service request added successfully
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  886):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  886):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  886): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState discover services
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service discovery started successfully
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  886):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  886): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6388): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log( 6388): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 6388): 
I/jxcore-log( 6388): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 6388): 
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  886):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  886):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  886):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 4488
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  886): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6388): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/jxcore-log( 6388): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6388): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1440): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1440): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  886): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  886):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  886):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  886):  primary type: 10-0050F204-5
D/WifiP2pService(  886):  secondary type: null
D/WifiP2pService(  886):  wps: 392
D/WifiP2pService(  886):  grpcapab: 0
D/WifiP2pService(  886):  devcapab: 37
D/WifiP2pService(  886):  status: 3
D/WifiP2pService(  886):  wfdInfo: null
D/WifiP2pService(  886):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/WifiP2pService(  886): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): restart: Restarting...
,D/WifiP2pService(  886): InactiveState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState clear service request
,F/libc    ( 1440): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1440 (wpa_supplicant)
I/libc    ( 1440): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  886): InactiveState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState add service request
,D/WifiP2pManager( 6388): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Service request added successfully
,E/QC-QMI  (  428): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/WifiP2pService(  886): InactiveState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6388): Failed to start the service discovery, got error code: 3
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 A3-1] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6388): onPeerLost: [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 6388): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6388): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] removed
D/io.jxcore.node.ConnectionHelper( 6388): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] not available
I/jxcore-log( 6388): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":false}]
I/jxcore-log( 6388): 
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {25de502d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  886): done {25de502d, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/jxcore-log( 6388): timeout now
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): weAreDoneNow
I/jxcore-log( 6388): 
,I/jxcore-log( 6388): done, now sending data to server
I/jxcore-log( 6388): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,E/WifiStateMachine(  886): Connection lost, restart supplicant
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: RESTARTING
,D/WifiP2pService(  886): InactiveState{ when=0 what=139268 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  886): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  886): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  886): failed to set BSSID: any
E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/WifiP2pService(  886): InactiveState{ when=-23ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-23ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
D/TCMD    (  483): Listening for incoming client connection request
,W/Settings( 1758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NativeCrypto( 1758): Read error: ssl=0xb91c40a0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1758): SSL shutdown failed: ssl=0xb91c40a0: I/O error during system call, Broken pipe
,E/WifiStateMachine(  886): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  886): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  886): connected time updated 481177
,D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  886): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=8113 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  886): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  886): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  886): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Disconnected - quitting
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  886): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
E/ConnectivityService(  886): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  886): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  886): Unexpected BatchedScanResults :null
E/WifiStateMachine(  886): [1,452,246,930,449 ms] noteScanEnd no scan source
,D/WifiP2pService(  886): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): discovery change broadcast false
D/WifiP2pService(  886): P2pDisablingState
D/WifiP2pService(  886): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): p2p socket connection lost
D/WifiP2pService(  886): P2pDisabledState
,D/WifiScanningService(  886): SCAN_AVAILABLE : 1
D/RttService(  886): SCAN_AVAILABLE : 1
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiScanningService(  886): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  886): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  886): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService(  886): P2pDisabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): stop: Stopping services
,D/WifiP2pService(  886): P2pDisabledState{ when=0 what=139298 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139298 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6388): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6388): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6388): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 6388): Shutting down VM
D/WifiP2pService(  886): P2pDisabledState{ when=0 what=139268 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139268 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pDisabledState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:832)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6388): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ResourcesManager( 8113): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8136 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7894:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_7894/cgroup.procs: No such file or directory
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
,D/TCMD    (  483): Listening for incoming client connection request
D/Tethering(  886): InitialState.processMessage what=4
,D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
,D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
,D/Tethering(  886): sendTetherStateChangedBroadcast 0, 0, 0
,W/ResourcesManager( 8136): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/Babel_SMS( 8136): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8136): MmsConfig.loadMmsSettings
I/Babel_SMS( 8136): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8136): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8136): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8136): MmsConfig.loadFromResources
,E/Babel_SMS( 8136): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8136): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,W/Settings( 8136): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TCMD    (  483): NL - Read 444 bytes from update socket.
,D/TCMD    (  483): NL - ignore NL message, type = 17
D/TCMD    (  483): Listening for incoming client connection request
,I/Babel_Crash( 8136): startup - clean
,I/Babel   ( 8136): deleted: false for 0
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/TCMD    (  483): NL - Read 444 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 17
D/TCMD    (  483): Listening for incoming client connection request
,W/VideoCapabilities( 8136): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8136): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8136): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8136): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8136): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8136): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8136): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8136): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Killing 7948:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7948/cgroup.procs: No such file or directory
,I/vclib   ( 8136): onServiceConnected
W/Babel   ( 8136): Attempted to change video mute state without an active call.
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  886): MasterInitialState.processMessage what=3
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2623): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8174 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1471): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2623): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2623): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2623): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2623): [debug] > CusSM.onRadioDown
D/CCE     ( 2623): Registering with Alarm Manager to restart CCE
,I/art     (  308): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 56.453ms
,D/CCE     ( 2623): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2623): Registering with Alarm Manager to restart CCE
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.115ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 24.789ms
,I/MusicStore( 8174): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8174): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8174): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8174): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8174): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8174): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1110c262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8174): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8174): GMSCore installation verified
,I/ConfigStore( 8174): Config Database version: 1
,I/MediaRouter( 8174): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8174): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8224 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8174): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8174): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 8007:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_8007/cgroup.procs: No such file or directory
,V/Mms     ( 8224): mnc/mcc: 
,V/Mms     ( 8224): tag: int value: recipientLimit - 20
,V/Mms     ( 8224): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8224): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 8224): tag: int value: maxSubjectLength - 80
V/Mms     ( 8224): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8224): tag: bool value: enableGroupMms - false
V/Mms     ( 8224):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,W/ResourcesManager( 8224): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8250 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8035:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 8250): Register our PhoneStateListener
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_8035/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8250): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 8250): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 6230): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6230): num queued entries: 0
,I/ActivityManager(  886): Killing 8136:com.google.android.talk/u0a70 (adj 15): empty #7
,I/iu.UploadsManager( 6230): num updated entries: 0
,I/iu.SyncManager( 6230): NEXT; no task
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_8136/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8273 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8293 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8113:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10008/pid_8113/cgroup.procs: No such file or directory
,W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  886): send {181e2df6, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/Babel_SMS( 8293): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8293): MmsConfig.loadMmsSettings
I/Babel_SMS( 8293): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8293): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8293): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8293): MmsConfig.loadFromResources
,E/Babel_SMS( 8293): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8293): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  886): Explicit concurrent mark sweep GC freed 33798(1994KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.609ms total 140.750ms
,W/Settings( 8293): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8293): startup - clean
,I/Babel   ( 8293): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8324 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8293): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8293): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8293): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8293): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8293): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8293): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8293): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8293): Unrecognized profile 2130706433 for video/avc
,D/WifiP2pService(  886): P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/vclib   ( 8293): onServiceConnected
W/Babel   ( 8293): Attempted to change video mute state without an active call.
I/Babel   ( 8293): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  886): Killing 8174:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8324): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8324): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8324): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8324):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8324):   adb logcat -s GAv4
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8324): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8324): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_8174/cgroup.procs: No such file or directory
,W/GAv4    ( 8324): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8324): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8324): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  886): ApnList is empty for checkDunConfigured()
,D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
D/Tethering(  886): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  483): NL - Read 1008 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
,D/TCMD    (  483): Listening for incoming client connection request
D/Tethering(  886): InitialState.processMessage what=4
D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
D/Tethering(  886):  1
D/Tethering(  886):  5
,D/Tethering(  886):  7
D/Tethering(  886): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  483): NL - Read 1008 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/QsoftapCmd(  290): Got softap fwreload command we are passing on
,D/SoftapController(  290): Softap fwReload - Ok
,D/CommandListener(  290): Setting iface cfg
,D/CommandListener(  290): Trying to bring down wlan0
D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  886): setWifiState: enabling
E/WifiStateMachine(  886): Supplicant start successful
D/WifiMonitor(  886): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  886): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 8367): Successfully initialized wpa_supplicant
I/wpa_supplicant( 8367): Long line in configuration file truncated
I/wpa_supplicant( 8367): rfkill: Cannot open RFKILL control device
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/libmdmdetect( 8367): ESOC framework not supported
E/Diag_Lib( 8367):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 8367): baseband property is set to [msm]
I/libmdmdetect( 8367): ESOC framework not supported
,E/wpa_supplicant( 8367):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8367): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8367): card_info[i].card_state: 0x0
E/wpa_supplicant( 8367): card_info[i].error_code: 0x0
E/wpa_supplicant( 8367): SIM/USIM not ready
E/wpa_supplicant( 8367): Error while reading SIM card status
,E/wpa_supplicant( 8367): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8367): card_info[i].card_state: 0x0
E/wpa_supplicant( 8367): card_info[i].error_code: 0x0
E/wpa_supplicant( 8367): SIM/USIM not ready
I/wpa_supplicant( 8367): eap_proxy: Card not ready
,I/WebViewFactory( 8324): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8324): Time to load native libraries: 1 ms (timestamps 8593-8594)
,I/LibraryLoader( 8324): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8324): Binding Chromium to main looper Looper (main, tid 1) {12771005}
,I/LibraryLoader( 8324): Expected native library version number "",actual native library version number ""
I/chromium( 8324): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8324): Initializing chromium process, singleProcess=true
,W/art     ( 8324): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8324): ApplicationContext is null in ApplicationStatus
,W/chromium( 8324): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 8324): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8324): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8324): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8324): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8324): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8324): Local Branch: 
I/Adreno-EGL( 8324): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8324): Local Patches: NONE
I/Adreno-EGL( 8324): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8324): Requires BLUETOOTH permission
,I/NSApplication( 8324): Starting up...
,E/wpa_supplicant( 8367): Line 31: unknown global field '�'.
E/wpa_supplicant( 8367): Line 31: Invalid configuration line '�'.
,I/wpa_supplicant( 8367): rfkill: Cannot open RFKILL control device
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/wpa_supplicant( 8367): baseband property is set to [msm]
I/libmdmdetect( 8367): ESOC framework not supported
,E/wpa_supplicant( 8367):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8367): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8367): card_info[i].card_state: 0x0
E/wpa_supplicant( 8367): card_info[i].error_code: 0x0
E/wpa_supplicant( 8367): SIM/USIM not ready
E/wpa_supplicant( 8367): Error while reading SIM card status
,E/wpa_supplicant( 8367): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8367): card_info[i].card_state: 0x0
E/wpa_supplicant( 8367): card_info[i].error_code: 0x0
E/wpa_supplicant( 8367): SIM/USIM not ready
I/wpa_supplicant( 8367): eap_proxy: Card not ready
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8404 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8224:com.android.mms/u0a23 (adj 15): empty #7
,I/wpa_supplicant( 8367): wlan0: CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_8224/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8423 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 8250:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_8250/cgroup.procs: No such file or directory
,W/ResourcesManager( 8423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): wifi_connect_to_supplicant, current pid is = 292
,D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  292): wifi_close_sockets: Exit
E/MDMCTBK (  292): Attach monitor thread
D/MDMCTBK (  292): wifi_ctrl_recv: Exiting
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
I/MDMCTBK (  292): createWifiMonitorThread: Started the wifi monitor thread -1195658376
D/MDMCTBK (  292): wifi_wait_on_socket: Enter monitor thread
D/MDMCTBK (  292): wifi_ctrl_recv: Exiting
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  292): wifi_close_sockets: Exit
D/MDMCTBK (  292): wifi_close_sockets: Exit
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8447 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8466 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 8293:com.google.android.talk/u0a70 (adj 15): empty #7
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/ActivityManager(  886): Killing 8273:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 8447): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/WifiStateMachine(  886): Supplicant connection established
E/WifiStateMachine(  886): setWifiState: enabled
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_8293/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_8273/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiConfigStore(  886): Loading config and enabling all networks 
,E/WifiConfigStore(  886):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  886):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  886): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  886): Setting external_sim to 1
D/WifiStateMachine(  886): Setting OUI to DA-A1-19
I/WifiNative-HAL(  886): startHal
E/wifi    (  886): getStaticLongField sWifiHalHandle 0xa2dc989c
D/wifi    (  886): halHandle = 0x0, mVM = 0xb8eb7310, mCls = 0x20179a
I/WifiNative-HAL(  886): Could not start hal
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/wpa_supplicant( 8367): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/wpa_supplicant( 8367): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_292-4\x00 that cannot receive messages
E/native  (  886): do suspend true
D/WifiP2pService(  886): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  886): SCAN_AVAILABLE : 3
D/RttService(  886): SCAN_AVAILABLE : 3
,D/WifiScanningService(  886): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  886): startHal
E/wifi    (  886): getStaticLongField sWifiHalHandle 0xa18f19cc
D/wifi    (  886): halHandle = 0x0, mVM = 0xb8eb7310, mCls = 0x20178a
,I/WifiNative-HAL(  886): Could not start hal
,E/WifiScanningService(  886): could not start HAL
,D/RttService(  886): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  290): Setting iface cfg
D/CommandListener(  290): Trying to bring up p2p0
,D/WifiMonitor(  886): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  886): P2pEnablingState
D/WifiP2pService(  886): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2p socket connection successful
D/WifiP2pService(  886): P2pEnabledState
D/WifiP2pService(  886): sending p2p connection changed broadcast
E/WifiStateMachine(  886): set country code US
,E/WifiStateMachine(  886): set frequency band 2
I/wpa_supplicant( 8367): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 8367): wlan0: Failed to initiate AP scan
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiNative-HAL(  886): p2pGetDeviceAddress
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiNative-HAL(  886): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  886): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  886): MCC mode enabled 0
,D/WifiP2pService(  886): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  886): sending p2p persistent groups changed broadcast
D/WifiP2pService(  886): InactiveState
D/WifiP2pService(  886): InactiveState{ when=-18ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-18ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): InactiveState{ when=-20ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-20ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/MusicStore( 8466): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8466): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8466): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8466): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8466): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8466): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8466): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8466): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8466): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1110c262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8466): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8466): GMSCore installation verified
,I/ConfigStore( 8466): Config Database version: 1
,I/MediaRouter( 8466): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8466): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8508 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8466): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8466): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 8324:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_8324/cgroup.procs: No such file or directory
,V/Mms     ( 8508): mnc/mcc: 
,V/Mms     ( 8508): tag: int value: recipientLimit - 20
V/Mms     ( 8508): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8508): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8508): tag: int value: maxSubjectLength - 80
V/Mms     ( 8508): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8508): tag: bool value: enableGroupMms - false
,V/Mms     ( 8508):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 8508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8543 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8404:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 24.919ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.360ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.703ms
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_8404/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8543): Register our PhoneStateListener
,I/wpa_supplicant( 8367): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/MobileConnectivityChangeReceiver( 8543): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 8543): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  886): Killing 8423:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_8423/cgroup.procs: No such file or directory
,I/wpa_supplicant( 8367): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 8367): wlan0: Failed to initiate AP scan
,D/WifiP2pService(  886): InactiveState{ when=-4ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-4ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledStateupdate channel list
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8562 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/WifiStateMachine(  886): [1,452,246,938,014 ms] noteScanEnd no scan source
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8585 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  886): Killing 8447:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_8447/cgroup.procs: No such file or directory
,W/ResourcesManager( 8585): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8585): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8585): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8585): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8585): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8585): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8585): MmsConfig.loadFromResources
,E/Babel_SMS( 8585): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8585): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8585): startup - clean
,I/Babel   ( 8585): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8616 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8585): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8585): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8585): Unsupported mime video/mpeg2
,I/wpa_supplicant( 8367): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 8367): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  886): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  886): [1,452,246,938,799 ms] noteScanEnd no scan source
,E/WifiStateMachine(  886): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2cc868ba sup_state=SCANNING debouncing=false
E/WifiConfigStore(  886):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/VideoCapabilities( 8585): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8585): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8585): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8585): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8585): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8585): onServiceConnected
,W/Babel   ( 8585): Attempted to change video mute state without an active call.
,I/Babel   ( 8585): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 8616): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8616):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8616):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8616): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
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
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 8367): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8616): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/wpa_supplicant( 8367): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 8367): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8616): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8616): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/art     (  886): Explicit concurrent mark sweep GC freed 29559(1524KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.667ms total 133.475ms
,I/ActivityManager(  886): Killing 8466:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/Tethering(  886): sendTetherStateChangedBroadcast 1, 0, 0
W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_8466/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/GAv4    ( 8616): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  886): Network connection established
E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  886): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
,E/WifiStateMachine(  886): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  886): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
,E/WifiStateMachine(  886): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  886): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  886): Start Dhcp Watchdog 3
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  886): do suspend false
,W/GAv4    ( 8616): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/wpa_supplicant( 8367): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  886): Unexpected BatchedScanResults :null
E/wpa_supplicant( 8367): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  886): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e22b406 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e22b406 target=com.android.internal.util.StateMachine$SmHandler }
,W/GAv4    ( 8616): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8616): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8616): Time to load native libraries: 2 ms (timestamps 1983-1985)
,I/LibraryLoader( 8616): Expected native library version number "",actual native library version number ""
,E/DHCPCD  ( 8665): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 8665): version 5.5.6 starting
E/DHCPCD  ( 8665): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 8665): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 8665): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,V/WebViewChromiumFactoryProvider( 8616): Binding Chromium to main looper Looper (main, tid 1) {12771005}
,I/LibraryLoader( 8616): Expected native library version number "",actual native library version number ""
I/chromium( 8616): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8616): Initializing chromium process, singleProcess=true
W/art     ( 8616): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8616): ApplicationContext is null in ApplicationStatus
,W/chromium( 8616): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8616): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8616): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8616): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8616): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8616): Local Branch: 
I/Adreno-EGL( 8616): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8616): Local Patches: NONE
I/Adreno-EGL( 8616): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DHCPCD  ( 8665): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 8665): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 8665): wlan0: sending REQUEST (xid 0x4f3b0450), next in 4.41 seconds
,W/AudioManagerAndroid( 8616): Requires BLUETOOTH permission
,I/NSApplication( 8616): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8696 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8508:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_8508/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8715 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8543:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_8543/cgroup.procs: No such file or directory
,W/ResourcesManager( 8715): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8738 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8585:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  886): Killing 8562:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 8738): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_8585/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2623): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_8562/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2623): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2623): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2623): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2623): onServiceConnected()
D/GetNotificationsWS( 2623): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2623): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8762 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  886): done {181e2df6, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [5514ms]
,I/ActivityManager(  886): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=8788 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8616:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_8616/cgroup.procs: No such file or directory
,W/ResourcesManager( 8788): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=250, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310960, SEQNUM=4584, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-1067, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8807 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6230:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  886): Client connection lost with reason: 4
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_6230/cgroup.procs: No such file or directory
,W/ResourcesManager( 8807): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8807): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8807): MmsConfig.loadMmsSettings
I/Babel_SMS( 8807): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8807): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8807): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8807): MmsConfig.loadFromResources
E/Babel_SMS( 8807): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8807): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8807): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8807): startup - clean
,I/Babel   ( 8807): deleted: false for 0
,W/VideoCapabilities( 8807): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8807): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8807): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8807): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8807): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8807): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8807): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8807): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Killing 8696:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_8696/cgroup.procs: No such file or directory
,I/vclib   ( 8807): onServiceConnected
,W/Babel   ( 8807): Attempted to change video mute state without an active call.
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/DHCPCD  ( 8665): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 8665): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 8665): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 8665): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 8665): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 8665): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 8665): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 20
D/TCMD    (  483): Listening for incoming client connection request
E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  886): WifiStateMachine DHCP successful
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  886): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  886): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  886): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  886): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  886): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService(  886): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  886): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  886): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  886): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  886):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,E/WifiStateMachine(  886): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/CSLegacyTypeTracker(  886): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  886): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 09:55:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452246942210], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452246942191]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Validated
D/ConnectivityService(  886): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  886): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): now: 567761 ,futureTime: 9223372036854775807
D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): now: 567761 ,futureTime: 9223372036854775807
D/PollingManager( 2623): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2623): now: 567761 ,futureTime: 9223372036854775807
D/OtaApp  ( 2623): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8905 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/OtaApp  ( 2623): [debug] > PollingManagerService, now: 567820 ,futureTime: 23094295
D/OtaApp  ( 2623): [debug] > Polling alarm set to expire at: 23094295 Current Time: 567820
,D/Central_PollingManager( 1471): now: 567823 ,futureTime: 86474057
,D/Central_PollingManager( 1471): Polling alarm set to expire at: 86474057 Current Time: 567823
,D/OtaApp  ( 2623): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2623): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2623): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2623): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/CCE     ( 2623): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2623): createDeviceIdOrLogin update_device
D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2623): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2623): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2623): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2623): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2623): createDeviceIdOrLogin update_device
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2623): set mOutstandingReq to true.
I/ Nonce  ( 2623):  Nonce getNonce 
I/ Nonce  ( 2623):  Nonce Request 
I/ Nonce  ( 2623):  Nonce execute Request 
,D/MMApiWebService( 2623): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2623): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2623): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2623): createDeviceIdOrLogin update_device
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2623): Not proxy app, so login/provision not allowed
,I/MusicStore( 8905): Database version: 120
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 5826(267KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 834us total 46.966ms
,I/art     (  886): Explicit concurrent mark sweep GC freed 29101(1454KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.625ms total 122.087ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8905): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/MMApiWebService( 2623): generating token using payload instead of using session token
,D/ Nonce  ( 2623):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2623): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8905): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8905): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8905): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8905): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8905): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8905): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8905): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1110c262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8905): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8905): GMSCore installation verified
,I/ConfigStore( 8905): Config Database version: 1
,I/MediaRouter( 8905): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8905): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 8905): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 8905): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8963 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8905): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 21.048ms
,I/GoogleURLConnFactory( 8905): Using platform SSLCertificateSocketFactory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.720ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.031ms
,I/ActivityManager(  886): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8982 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8738:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 8963): mnc/mcc: 
V/Mms     ( 8963): tag: int value: recipientLimit - 20
V/Mms     ( 8963): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8963): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8963): tag: int value: maxSubjectLength - 80
V/Mms     ( 8963): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8963): tag: bool value: enableGroupMms - false
,V/Mms     ( 8963):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_8738/cgroup.procs: No such file or directory
,W/ResourcesManager( 8982): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8982): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 8982): VM with version 2.1.0 has multidex support
I/MultiDex( 8982): install
I/MultiDex( 8982): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9006 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 8762:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/PhoneMonitor( 9006): Register our PhoneStateListener
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_8762/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 9006): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9006): onReceive CONNECTIVITY_CHANGE networkType=1
,V/JNIHelp ( 8982): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8982): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8982): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e76c5b9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8982): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  886): Killing 8807:com.google.android.talk/u0a70 (adj 15): empty #7
,D/NativeLibraryUtils( 8982): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_8807/cgroup.procs: No such file or directory
,I/CheckinService( 8982): Checkin interval check for package: unspecified last checkin: 1452246630451 min interval config: 0 actual interval: 316238
,I/art     ( 6198): Explicit concurrent mark sweep GC freed 1890(71KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 323us total 22.882ms
,I/CheckinService( 8982): Disabling old GoogleServicesFramework version
,I/CheckinService( 8982): Checking schedule, now: 1452246946746 next: 1452246660420
I/CheckinService( 8982): active receiver: enabled
,I/CheckinService( 8982): Preparing to send checkin request
,I/EventLogService( 8982): Accumulating logs since 1452246626515
,I/iu.SyncManager( 8982): SYNC; picasa accounts
,D/NetworkLogImpl( 8982): Loaded NetworkSpeedPredictor
,I/iu.Environment( 8982): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 8982): num queued entries: 0
,I/iu.UploadsManager( 8982): num updated entries: 0
,I/iu.SyncManager( 8982): NEXT; no task
,I/art     ( 8982): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8982): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9054 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ Nonce  ( 2623):  Nonce Reponse 
D/        ( 2623): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"e0b239f5-a8a9-4695-ae35-603aacf3e8cc"}
D/MMApiWSBase( 2623): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2623):  Nonce Handle Reponse 
D/MMApiProvisionService( 2623): mOutstandingReq set to false
,I/CheckinRequestBuilder( 8982): Checkin reason type: 8 attempt count: 1
,D/WifiService(  886): New client listening to asynchronous messages
E/ActivityThread( 8982): Failed to find provider info for com.google.android.wearable.settings
,D/MMApiProvisionService( 2623):  pTime 1452107623780 sExp 172742 cTime 1452246947146 tTime 1452280365780
D/MMApiProvisionService( 2623):  No login Required 
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9082 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  886): Explicit concurrent mark sweep GC freed 12018(589KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.394ms total 118.055ms
,I/ActivityManager(  886): Killing 8788:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10008/pid_8788/cgroup.procs: No such file or directory
,W/ResourcesManager( 9082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9104 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 9104): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9104): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/DataUsage( 2623): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2623): publish the event [tag = MOT_CCE event name = LOG]
,I/MultiDex( 9104): VM with version 2.1.0 has multidex support
I/MultiDex( 9104): install
I/MultiDex( 9104): VM has multidex support, MultiDex support library is disabled.
,I/Babel_SMS( 9082): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9082): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9082): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9082): MmsConfig.loadFromDatabase
,V/JNIHelp ( 9104): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel_SMS( 9082): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9082): MmsConfig.loadFromResources
E/Babel_SMS( 9082): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9082): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 9104): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9104): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@323f649b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9104): Installed default security provider GmsCore_OpenSSL
,W/Settings( 9082): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9082): startup - clean
,I/art     ( 9104): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9104): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel   ( 9082): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9138 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 9104): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  295): App is not loaded in QSEE
,W/VideoCapabilities( 9082): Unrecognized profile 2130706433 for video/avc
D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,W/AudioCapabilities( 9082): Unsupported mime audio/amr-wb-plus
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbef0b4e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb89bba60, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a43fc8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a8f7c0, idLength=0xb55cc730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1472350140
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a35538
D/DrmWidevineDash(  295): message_length=1591, signature=0xb89ae988, signature_length=3042756372
,W/VideoCapabilities( 9082): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9082): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9082): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9082): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9082): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9082): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 9138): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9138):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9138):   adb logcat -s GAv4
I/vclib   ( 9082): onServiceConnected
W/Babel   ( 9082): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9138): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 9138): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/Babel   ( 9082): connection state changed from UNKNOWN to CONNECTED
,W/ContextImpl( 9138): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  886): Killing 8715:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
W/ContextImpl( 9138): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9138): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9138): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9138): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_8715/cgroup.procs: No such file or directory
,I/WebViewFactory( 9138): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9138): Time to load native libraries: 2 ms (timestamps 1155-1157)
I/LibraryLoader( 9138): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9138): Binding Chromium to main looper Looper (main, tid 1) {337eaa8b}
,I/LibraryLoader( 9138): Expected native library version number "",actual native library version number ""
I/chromium( 9138): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9138): Initializing chromium process, singleProcess=true
,W/art     ( 9138): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9138): ApplicationContext is null in ApplicationStatus
,W/chromium( 9138): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9138): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9138): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9138): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9138): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9138): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9138): Local Branch: 
I/Adreno-EGL( 9138): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9138): Local Patches: NONE
I/Adreno-EGL( 9138): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 9138): Starting up...
,W/AudioManagerAndroid( 9138): Requires BLUETOOTH permission
,I/dex2oat ( 9204): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9206 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 8905:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_8905/cgroup.procs: No such file or directory
,I/dex2oat ( 9204): dex2oat took 83.819ms (threads: 4)
,I/Adreno-EGL( 9104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9104): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9104): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9104): Local Branch: 
I/Adreno-EGL( 9104): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9104): Local Patches: NONE
I/Adreno-EGL( 9104): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9104): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9104): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9104): Local Branch: 
I/Adreno-EGL( 9104): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9104): Local Patches: NONE
I/Adreno-EGL( 9104): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9230 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 8963:com.android.mms/u0a23 (adj 15): empty #7
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_8963/cgroup.procs: No such file or directory
,W/ResourcesManager( 9230): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb54cc960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb89bbd88, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb89bbf08, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a8f800, idLength=0xb55cc730
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=391968596
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89a5e30
D/DrmWidevineDash(  295): message_length=1626, signature=0xb89ae988, signature_length=3042756372
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9260 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 9104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9104): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9104): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9104): Local Branch: 
I/Adreno-EGL( 9104): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9104): Local Patches: NONE
I/Adreno-EGL( 9104): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  886): Killing 9054:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/Adreno-EGL( 9104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9104): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9104): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9104): Local Branch: 
I/Adreno-EGL( 9104): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9104): Local Patches: NONE
I/Adreno-EGL( 9104): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ContactLocale( 9260): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 9006:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_9054/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2623): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_9006/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2623): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2623): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2623): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2623): onServiceConnected()
D/GetNotificationsWS( 2623): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2623): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2623): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2623): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2623): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2623): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  886): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2623): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2623): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2623): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2623): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1758): callingUid 10016, callindPid: 1758
,E/MDM     ( 1758): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/OtaApp  ( 2623): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2623): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 8982): Restart initialization of location
,D/OtaApp  ( 2623): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2623): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2623): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1758): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,W/FusedLocationProvider( 1758): location=null
,I/CheckinRequestBuilder( 8982): Classify the device as Phone.
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9302 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/IcingInternalCorpora( 8982): getNumBytesRead when not calculated.
,I/CheckinTask( 8982): Sending checkin request (9453 bytes)
,E/MDM     ( 1758): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 8982): Restart initialization of location
,D/AuthorizationBluetoothService( 1758): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1758): No location to return for getLastLocation()
,W/FusedLocationProvider( 1758): location=null
,I/ActivityManager(  886): Killing 9138:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_9138/cgroup.procs: No such file or directory
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  292): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  292): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/CheckinRequestBuilder( 8982): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 8982): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  886): Explicit concurrent mark sweep GC freed 11934(555KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.544ms total 118.565ms
,I/CheckinRequestBuilder( 8982): Classify the device as Phone.
,I/CheckinTask( 8982): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 8982): Checking schedule, now: 1452246951241 next: 1452848088234
,I/CheckinService( 8982): active receiver: disabled
,D/CheckinService( 8982): Recording last checkin time for package unspecified as 1452246951252
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9345 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 23.092ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 19.701ms
,D/PhoneMonitor( 9345): Register our PhoneStateListener
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.041ms
,V/SetupWizard( 9345): Connected to Gservices successfully
,I/ActivityManager(  886): Killing 9206:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_9206/cgroup.procs: No such file or directory
,D/GCM     ( 1758): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  886): Killing 9230:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_9230/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 9082:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_9082/cgroup.procs: No such file or directory
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9368 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@267c4764
,I/GCoreNlp( 1758): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9405 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/ProcessCpuTracker(  886): Skipping unknown process pid 9394
,W/ProcessCpuTracker(  886): Skipping unknown process pid 9397
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=9414 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 9260:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  886): Killing 9302:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_9260/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_9302/cgroup.procs: No such file or directory
,W/ResourcesManager( 9414): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9414): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9414): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9414): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9414): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9414): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9414): MmsConfig.loadFromResources
,E/Babel_SMS( 9414): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9414): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9414): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 9414): startup - clean
,I/Babel   ( 9414): deleted: false for 0
,I/ActivityManager(  886): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=9457 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 9414): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9414): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9414): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9414): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9414): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9414): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9414): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9414): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9481 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 9345:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 9457): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_9345/cgroup.procs: No such file or directory
,I/vclib   ( 9414): onServiceConnected
,W/Babel   ( 9414): Attempted to change video mute state without an active call.
,W/asset   ( 9481): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 9481): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9481): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9481): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 9414): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9414): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 8982): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 9368): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 8982): Null package name or gms related package.  Ignoreing.
W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f430ec0 new=com.google.android.velvet.VelvetApplication@f430ec0
V/JNIHelp ( 9414): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9515 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 9414): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9414): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 9515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 9368): UpdateCorporaTask done [took 145 ms] updated apps [took 145 ms] 
,I/Icing   ( 8982): Storage manager: low false usage 1.71MB avail 3.12GB capacity 4.85GB
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9550 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 9104:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/Icing   ( 8982): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_9104/cgroup.procs: No such file or directory
,D/Finsky  ( 9550): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 8982): Internal init done: storage state 0
,I/Icing   ( 8982): Post-init done
,I/Icing   ( 8982): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 9550): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9550): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9550): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  886): Explicit concurrent mark sweep GC freed 17442(896KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.400ms total 120.210ms
,D/Finsky  ( 9550): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 9550): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 9550): Skipping gmscore version check
,D/Finsky  ( 9550): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 9550): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  886): Killing 9405:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_9405/cgroup.procs: No such file or directory
,I/Icing   ( 8982): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 8982): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 8982): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  886): Killing 9481:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_9481/cgroup.procs: No such file or directory
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  292): NetlinkHandler, interfaceAdded
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
E/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  292): , Wifi = 0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager(  886): Killing 9414:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_9414/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/CheckinService( 8982): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  292): NetlinkHandler, interfaceAdded
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
E/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  292): , Wifi = 0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
,E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {25de502d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  886): done {25de502d, *walarm*:android.content.syncmanager.SYNC_ALARM} [13ms]
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
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
,W/bt-btif ( 2491): info:x10
,D/        ( 2491): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2491): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2491): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2491): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2491): Entering PendingCommandState State
,D/BluetoothManagerService(  886): Message: 20
D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fe6eec1:true
,I/LaunchCheckinHandler(  886): cleanup(): cleared. Last call was 35504 ms ago
I/ActivityManager(  886): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=9611 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 9611): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  886): Message: 20
D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d561da7:true
,I/BluetoothBondStateMachine( 2491): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2491): Failed to remove device: B0:C5:59:3F:75:69
,I/ActivityManager(  886): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=9644 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2491): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,D/BluetoothAdapterService( 2491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2abb4d66
,I/ActivityManager(  886): Killing 9368:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
I/BluetoothBondStateMachine( 2491): StableState(): Entering Off State
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_9368/cgroup.procs: No such file or directory
,D/BluetoothMetrics( 2491): btclass5a020c
,D/Checkin ( 2491): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2491): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6388): Incoming connection accepted
,W/bt-btif ( 2491): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2491): bta_dm_pm_ssr:2, lat:1200
,W/ResourcesManager( 9644): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/google-breakpad( 9666): -----BEGIN BREAKPAD MICRODUMP-----
W/google-breakpad( 9666): O A arm 04 armv7l 3.4.42-g48d3b85 #1 SMP PREEMPT Tue Jan 6 18:27:11 CST 2015
W/google-breakpad( 9666): S 0 A34FFFF0 A34FF000 00008000
,W/google-breakpad( 9666): S A34FF000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad( 9666): S A34FF180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad( 9666): S A34FF300 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9666): S A34FF480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9666): S A34FF600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9666): S A34FF780 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000205B0DB900000000C2250000105B0DB9205B0DB900000000001000000010A1B40000000000000000F4180000205B0DB9105B0DB9C0F84FA37003000000000000C0F84FA3E48DF1B6105B0DB980FC4FA300FD4FA3A8F479A99BD828A90B0000000000000002000000F0DF4FA3000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9666): S A34FF900 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000009D1F000000000000000000000000000000003FB400000000002000000E00000017000000041200006871406FE0A5E76F900AD7228017D822C40000006871406FE0A5E76F8017D82238A6E76F90B5C1BA900AD72270F85FA3F0DF4FA3F0FF4FA36D2AB2713C2AB27130000EA0F0DF4FA30412000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000015046562001000000000000000000000000000000000000000000000000000000000000000000004CFD000000000000D0FFFFFF3CE4377E983A0000000000003100000081FFFFFF0000000000000000
W/google-breakpad( 9666): S A34FFA80 00400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E2F7032702F6274636F6E6E6563746F726C69622F7574696C732F426C7565746F6F7468536F636B6574496F546872656100000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF1300006000000000000000409CC7FBC03465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9666): S A34FFC00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C97F3A4000000000B00000080FC4FA300FD4FA30000000053D928A9089B91A0000000000400004028893FB96871406FC40000006871406FE0A5E76F8017D82238A6E76F90B5C1BAE099F2B60B0000000000000002000000F0DF4FA300000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003FB400000000002000000E00000017000000041200006871406FE0A5E76F900AD7228017D822C40000006871406FE0A5E76F8017D82238A6E76F90B5C1BA900AD72270F85FA3F0DF4FA3F0FF4FA36D2AB2713C2AB27130000EA0F0DF4FA3041200000000000000000000000000000000000000000000
W/google-breakpad( 9666): S A34FFD80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000015046562001000000000000000000000000000000000000000000000000000000000000000000004CFD000000000000D0FFFFFF3CE4377E983A0000000000003100000081FFFFFF000000000000000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E2F7032702F6274636F6E6E6563746F726C69622F7574696C732F426C7565746F6F7468536F636B6574496F546872656100000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF1300006000000000000000409CC7FBC0
W/google-breakpad( 9666): S A34FFF00 3465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AD70A0E3AD0090EF6871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3500E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
D/BluetoothManagerService(  886): Message: 20
D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d38c2f2:true
W/google-breakpad( 9666): S A3500F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501100 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501280 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501400 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
I/ActivityManager(  886): Killing 9457:android.process.acore/u0a7 (adj 15): empty #7
W/google-breakpad( 9666): S A3501580 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501700 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501880 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3501E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502000 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502180 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502300 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502480 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502600 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502780 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502900 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3502F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
,W/google-breakpad( 9666): S A3503080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3503F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504100 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504280 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504400 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504580 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504700 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504880 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3504E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505000 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505180 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505300 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505480 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505600 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505780 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505900 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3505F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB271
W/google-breakpad( 9666): S A3506F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F8017D82238A6E76F900AD7226D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F8017D822E0A5E76F900AD722B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F
W/google-breakpad( 9666): C 060000406871406FE0A5E76F900AD7228017D822C40000006871406FE0A5E76F8017D82238A6E76F90B5C1BA900AD72270F85FA3F0DF4FA3F0FF4FA36D2AB2713C2AB27130000EA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 9666): M B6F3A000 00000000 00003000 E9668E25F5C80EF4F2CC4AB624E387BF0 app_process32
W/google-breakpad( 9666): M A05B3000 00000000 00AB8000 F83F9605A81C561DE740DB94A502D11C0 libjxcore.so
W/google-breakpad( 9666): M A4494000 00000000 0000A000 BB53B487721763CEB1E8693EAC1446400 libqservice.so
W/google-breakpad( 9666): M A449E000 00000000 00007000 48FE648D1FA5FCBE53FCA043FD7608CB0 libqdutils.so
W/google-breakpad( 9666): M A44A5000 00000000 00005000 BEDF6C78A529DBAC1032A12C9142745E0 libmemalloc.so
W/google-breakpad( 9666): M A44AA000 00000000 00007000 7940278696CC504CA766F27B36AC080A0 gralloc.msm8226.so
W/google-breakpad( 9666): M A5A5C000 00000000 00452000 1C3C15CCBCD1E8D40558461B307435E60 libsc-a3xx.so
W/google-breakpad( 9666): M A7225000 00000000 0000C000 FE1E24201276FD291234996A311FBB9C0 eglsubAndroid.so
W/google-breakpad( 9666): M A7B45000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad( 9666): M ADF45000 00000000 00003000 932CC9935B065A05D39E38681E0A5F2E0 libwebviewchromium_loader.so
W/google-breakpad( 9666): M ADF48000 00000000 00010000 62690FE7B4748EF8151B01903B27608D0 libandroid.so
W/google-breakpad( 9666): M ADF58000 00000000 0013A000 9C03AF685FCBD8E590150A91E97E640F0 libGLESv2_adreno.so
,W/google-breakpad( 9666): M AE093000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad( 9666): M AE0C7000 00000000 00027000 13BED457CB8AEE0E8E47FB48F3E826420 libgsl.so
W/google-breakpad( 9666): M AE0EF000 00000000 00029000 C29A639A4A36C88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad( 9666): M AE6B6000 00000000 00018000 0F5D893354D9DF6AC2763E175086C0730 libjavacrypto.so
W/google-breakpad( 9666): M AE6CE000 00000000 00009000 0D2147262F4305E3AED211CB96FC96BA0 librs_jni.so
W/google-breakpad( 9666): M AE6D7000 00000000 00006000 ED6A76B3930E7139A7512B4E28EBAC070 libaudioeffect_jni.so
W/google-breakpad( 9666): M AE6DD000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad( 9666): M AE6E1000 00000000 0000E000 D02CB251CF8787A770DE2CFDC52A2B040 libstagefright_amrnb_common.so
W/google-breakpad( 9666): M AE6EF000 00000000 0001B000 F59669C665FE4B073886A8DAAECEA86F0 libvorbisidec.so
W/google-breakpad( 9666): M AE70A000 00000000 00004000 9FC00D0B150FE9FC57763A76206D1D550 libstagefright_yuv.so
W/google-breakpad( 9666): M AE70E000 00000000 0001F000 C2D643DD7028582A8EAF64D04750FE800 libstagefright_omx.so
W/google-breakpad( 9666): M AE72D000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
W/google-breakpad( 9666): M AE730000 00000000 00007000 741CC494F5299870A1C62FD71E37AE5F0 libstagefright_avc_common.so
W/google-breakpad( 9666): M AE737000 00000000 00005000 D3EA22EB9F383751AB500AE5951F0DB30 libpowermanager.so
W/google-breakpad( 9666): M AE73C000 00000000 0003C000 F19A7DFF3B6F3AF94EAE23CA21905BAD0 libopus.so
W/google-breakpad( 9666): M AE778000 00000000 0001B000 87AFCC5E47ED503148F1AA03777E88590 libdrmframework.so
W/google-breakpad( 9666): M AE793000 00000000 00127000 A7BBF189464222DE263F6ABC36940BBC0 libstagefright.so
W/google-breakpad( 9666): M AE8BA000 00000000 00017000 52DC9A344B2F37EBE6D980F419DD79800 libmtp.so
W/google-breakpad( 9666): M AE8D1000 00000000 0002C000 84F170F995DC0EAD4100002C63E26D090 libexif.so
,W/google-breakpad( 9666): M AE8FD000 00000000 0003E000 24984B90B04E5F6F6034503CCF81A3530 libmedia_jni.so
,W/google-breakpad( 9666): M B0D5F000 00000000 00003000 41762ACB6188785E5EF211BB8F33F0580 memtrack.msm8226.so
,W/google-breakpad( 9666): M B2465000 00000000 00038000 FE4EB304B0639D600DFB5871136831C50 libjavacore.so
,W/google-breakpad( 9666): M B24DA000 00000000 0000B000 D2AB7418CCD8D2EBF766A47707CC1E530 libjhead.so
,W/google-breakpad( 9666): M B24FB000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
,W/google-breakpad( 9666): M B24FE000 00000000 00008000 F2B1298EE4C6EA0900CDACD17FB5C16B0 libcompiler_rt.so
,W/google-breakpad( 9666): M B2506000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
,W/google-breakpad( 9666): M B43F6000 00000000 00004000 F007D0E8B4B1447628068777E701EBBC0 libwebviewchromium_plat_support.so
W/google-breakpad( 9666): M B4E01000 00000000 00009000 CF0326786BDECFB45A519C7005E851000 libbacktrace_libc++.so
W/google-breakpad( 9666): M B4E0B000 00000000 0030F000 3DD3B70782F1361DED6013B85580C7EC0 libart.so
W/google-breakpad( 9666): M B513D000 00000000 00004000 3CBDF0DE27B9554508AD60FDC96CBC620 libusbhost.so
W/google-breakpad( 9666): M B5141000 00000000 00041000 CE3E76CDA5E80C14EBD7C841E8D84F650 libssl.so
W/google-breakpad( 9666): M B5182000 00000000 000FF000 8DBA0B7AE9FE1796BB2D267C8FA450650 libsqlite.so
W/google-breakpad( 9666): M B5281000 00000000 0000F000 F954BA248E12C9AF32F54434F977FEF80 libsoundtrigger.so
W/google-breakpad( 9666): M B5290000 00000000 0000F000 113A72FAE76EEFA7090E693F3549A3010 libselinux.so
,W/google-breakpad( 9666): M B529F000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
,W/google-breakpad( 9666): M B52A3000 00000000 0045B000 83C5B450634DDB5C4FC41CA61A35B3740 libpdfium.so
W/google-breakpad( 9666): M B5703000 00000000 00004000 417CB14A7DB4E6A1B990FD8AC53764470 libnetd_client.so
,W/google-breakpad( 9666): M B5707000 00000000 00007000 F2C71E0D275A5D80BD35EE70ECFD70FD0 libnativehelper.so
W/google-breakpad( 9666): M B570E000 00000000 00004000 1DD26A12D05B7F3D88CEF118B5CB04390 libnativebridge.so
W/google-breakpad( 9666): M B5712000 00000000 0000C000 31B45FE1FA6CC789F945332C6FECF9750 libminikin.so
W/google-breakpad( 9666): M B571E000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
,W/google-breakpad( 9666): M B5721000 00000000 00015000 60A6E0B998632198B80EB0941121CD710 libstagefright_foundation.so
,W/google-breakpad( 9666): M B5736000 00000000 00051000 6E42AB0836D73C21533C08A98EE7B24C0 libsonivox.so
,W/google-breakpad( 9666): M B578C000 00000000 0000F000 E43E7FA869E4BCDAA3CC9601DF5A6A520 libcommon_time_client.so
,W/google-breakpad( 9666): M B579B000 00000000 0000A000 6B713D36804D7F05D55318F859E1E1400 libnbaio.so
,W/google-breakpad( 9666): M B57A5000 00000000 0009B000 64619D291C1C60AA9DC086C283338A6D0 libmedia.so
,W/google-breakpad( 9666): M B5840000 00000000 0003D000 C38209953DA7DBBD456E5C2897B2FC150 libinputflinger.so
,W/google-breakpad( 9666): M B587D000 00000000 0001B000 74F168449838583071D83A6436D107740 libinput.so
,W/google-breakpad( 9666): M B5898000 00000000 0000D000 5B082E821F342B59EB7E98B4A5A1B7D10 libimg_utils.so
,W/google-breakpad( 9666): M B58A5000 00000000 00032000 89A4F06810290EEAF309C12642A3ECFA0 libjpeg.so
,W/google-breakpad( 9666): M B58D8000 00000000 00231000 70FC6B965940F66B510A2E7DDA905A3F0 libskia.so
,W/google-breakpad( 9666): M B5B0E000 00000000 0001D000 FC19A9DAC51914495386BF19318E22EA0 libRScpp.so
W/google-breakpad( 9666): M B5B2B000 00000000 00028000 6E7220E587365DE4D76F850674158CB90 libpng.so
,W/google-breakpad( 9666): M B5B53000 00000000 0005A000 659F1470013A04F7702E4BAB65F034E70 libft2.so
,W/google-breakpad( 9666): M B5BAD000 00000000 0003D000 44717FC6883CFF24CB7D5AB323BA6DB00 libbcinfo.so
W/google-breakpad( 9666): M B5BEA000 00000000 00023000 53CBA510148C055D91FC2FE6ABEB7AF80 libbcc.so
W/google-breakpad( 9666): M B5C2D000 00000000 00094000 D27BE45ECDACFCE9AD319AFCC4384FDE0 libc++.so
W/google-breakpad( 9666): M B5CC3000 00000000 00938000 309278A31B6D547CF87ABF9850B977170 libLLVM.so
W/google-breakpad( 9666): M B6602000 00000000 0003A000 D276EA3D64313AC3429FA50C13E048AD0 libRS.so
,W/google-breakpad( 9666): M B663C000 00000000 0004C000 676E6078730EA64301EE765F510315BD0 libhwui.so
,W/google-breakpad( 9666): M B6688000 00000000 00110000 1B1FD653750DE88B86D7E83095EE37160 libicuuc.so
,W/google-breakpad( 9666): M B679C000 00000000 00006000 F4F99E4A6E63BF8C8005D96B2BAC8CEB0 libgabi++.so
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_9457/cgroup.procs: No such file or directory
,W/google-breakpad( 9666): M B67A2000 00000000 00167000 237F53C12084A7F42405B410FDE8B4020 libicui18n.so
,W/google-breakpad( 9666): M B6909000 00000000 00048000 AC5AE16EC01F4362C8E63DF66565090D0 libharfbuzz_ng.so
,W/google-breakpad( 9666): M B6951000 00000000 00005000 4E8926B7F3B40489DDA2954EC97B8D220 libwpa_client.so
,W/google-breakpad( 9666): M B6956000 00000000 00007000 ADCE932B3390EC21752A7A6149AA6DA60 libnetutils.so
,W/google-breakpad( 9666): M B695D000 00000000 00007000 F71457D34715CA9491C2A031B5F4D2DE0 libhardware_legacy.so
,W/google-breakpad( 9666): M B6965000 00000000 00017000 B98E65710C415C83E972EBDC1EB52AC00 libexpat.so
W/google-breakpad( 9666): M B697C000 00000000 0015E000 00A487ECBEDBE59A4AF1305D7B4C982D0 libcrypto.so
,W/google-breakpad( 9666): M B6ADD000 00000000 00003000 914425D16565257955F7E1574360B71F0 libhardware.so
,W/google-breakpad( 9666): M B6AE0000 00000000 0000C000 4C6A07EB894125D1DB41E0E4195358730 libui.so
W/google-breakpad( 9666): M B6AEC000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
W/google-breakpad( 9666): M B6AEF000 00000000 0004F000 559E784386AC5E53A9D4D7F9916AA7F90 libgui.so
,W/google-breakpad( 9666): M B6B3E000 00000000 00008000 D86968E73262725A4BA707DF821962E60 libcamera_metadata.so
,W/google-breakpad( 9666): M B6B46000 00000000 0003A000 116F763683FB0C7DD45AACC16324410B0 libcamera_client.so
,W/google-breakpad( 9666): M B6B80000 00000000 00006000 AC1D054A26491BE96E8BCCB1E5F2926F0 libspeexresampler.so
W/google-breakpad( 9666): M B6B86000 00000000 00006000 C7B066E606462D658A4D7A9F2EAA61D80 libaudioutils.so
,W/google-breakpad( 9666): M B6B8C000 00000000 0001A000 03AD92B0BEDAA751C0016E97AE374CAE0 libz.so
,W/google-breakpad( 9666): M B6BA6000 00000000 00030000 AC6C388A36224541CD74B35818111B760 libbinder.so
,W/google-breakpad( 9666): M B6BD6000 00000000 00028000 4369ED7B14428F57EF37081E2AA076720 libandroidfw.so
W/google-breakpad( 9666): M B6BFE000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
W/google-breakpad( 9666): M B6C09000 00000000 00007000 EFE6AB19F4060BCECF8CF0E68958C2F60 libGLESv1_CM.so
W/google-breakpad( 9666): M B6C10000 00000000 00004000 C91EAF69D18F0D499BD58532BBA173690 libETC1.so
W/google-breakpad( 9666): M B6C14000 00000000 00004000 7AE0C00FAEDEA3E81109CC784D49A6960 libunwind-ptrace.so
W/google-breakpad( 9666): M B6C18000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
,W/google-breakpad( 9666): M B6C6C000 00000000 00007000 3874D35A672DF92604963290963F44990 libgccdemangle.so
W/google-breakpad( 9666): M B6C75000 00000000 00008000 45B51BF91D330E793C9142C2617D7A8E0 libbacktrace.so
W/google-breakpad( 9666): M B6C7E000 00000000 00018000 4929CACB90B1756D54AABC210956A8720 libutils.so
W/google-breakpad( 9666): M B6C96000 00000000 0003B000 2FE003E5119C67BABE1A9FAB459A5A5D0 libstlport.so
W/google-breakpad( 9666): M B6CD1000 00000000 0000D000 89C05C3E2CA4C0CEE048FF2C8DBE53BD0 libcutils.so
,W/google-breakpad( 9666): M B6CDF000 00000000 00071000 A12BAF7D82BE28EC681730452D351E880 libGLES_trace.so
,W/google-breakpad( 9666): M B6D50000 00000000 00068000 924D4C5446BF1132A902C15519E5C4FD0 libEGL.so
,W/google-breakpad( 9666): M B6DBB000 00000000 000DD000 ECF593F4D6A605B04E7323D33A3802CE0 libandroid_runtime.so
,W/google-breakpad( 9666): M B6E98000 00000000 00004000 DFCD7772F3A5BD1E84A50C4DBFDE6F570 libstdc++.so
W/google-breakpad( 9666): M B6E9C000 00000000 00019000 75E20BCCFF30FFEC047C70BDA7F7144B0 libm.so
,W/google-breakpad( 9666): M B6EB6000 00000000 00007000 8CAFD8BD12AF3E16BE6445415809E8D90 liblog.so
,W/google-breakpad( 9666): M B6EBE000 00000000 0005A000 11CB106704827A02E2DDB8936FB8C13B0 libc.so
W/google-breakpad( 9666): M B6F22000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/google-breakpad( 9666): M B6F2A000 00000000 0000F000 F27F6D6C09C0D8A16DDA00721CEC963C0 linker
W/google-breakpad( 9666): -----END BREAKPAD MICRODUMP-----
,W/google-breakpad( 6388): ### ### ### ### ### ### ### ### ### ### ### ### ###
W/google-breakpad( 6388): Chrome build fingerprint:
,W/google-breakpad( 6388): 0.0.1
W/google-breakpad( 6388): 18
W/google-breakpad( 6388): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 6388): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 6388): ### WebView Version 44.0.2403.90 (code 240309000)
F/libc    ( 6388): Fatal signal 11 (SIGSEGV), code 2, fault addr 0xa34fdff0 in tid 8093 (Thread-769)
,I/DEBUG   ( 6408): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   ( 6408): Build fingerprint: 'motorola/thea_reteu/thea:5.0.2/LXB22.46-28/27:user/release-keys'
,I/DEBUG   ( 6408): Revision: 'p300'
I/DEBUG   ( 6408): ABI: 'arm'
I/DEBUG   ( 6408): pid: 6388, tid: 8093, name: Thread-769  >>> com.test.thalitest <<<
I/DEBUG   ( 6408): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa34fdff0
,I/DEBUG   ( 6408):     r0 6f407168  r1 6fe7a5e0  r2 22d70a90  r3 22d81780
,I/DEBUG   ( 6408):     r4 000000c4  r5 6f407168  r6 6fe7a5e0  r7 22d81780
I/DEBUG   ( 6408):     r8 6fe7a638  r9 bac1b590  sl 22d70a90  fp a35ff870
I/DEBUG   ( 6408):     ip a34fdff0  sp a34ffff0  lr 71b22a6d  pc 71b22a3c  cpsr a00e0030
I/DEBUG   ( 6408): 
I/DEBUG   ( 6408): backtrace:
I/DEBUG   ( 6408):     #00 pc 00091a3c  /system/framework/arm/boot.oat
I/DEBUG   ( 6408):     #01 pc 00091a6b  /system/framework/arm/boot.oat
,I/DEBUG   ( 6408): 
I/DEBUG   ( 6408): Tombstone written to: /data/tombstones/tombstone_09
,I/BootReceiver(  886): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,I/WindowState(  886): WIN DEATH: Window{30d1acc5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  886): Client connection lost with reason: 4
,W/bt-btif ( 2491): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,E/bt-btif ( 2491): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/Zygote  (  308): Process 6388 exited due to signal (11)
,I/ActivityManager(  886): Process com.test.thalitest (pid 6388) has died
,E/bt-btm  ( 2491): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2491): onReceive
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=9683 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  886): Message: 20
D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d8c1c3e:true
,I/BTConnectionReceiver( 9683): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,D/btif_config_util( 2491): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9723 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.312ms
,I/BluetoothClassifier( 9683): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 320us total 20.632ms
,W/bt-btif ( 2491): info:x10
D/        ( 2491): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
I/ActivityManager(  886): Killing 9515:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 24.746ms
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_9515/cgroup.procs: No such file or directory
,D/btif_config_util( 2491): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2491): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,W/bt-btif ( 2491): info:x10
,D/        ( 2491): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,D/btif_config_util( 2491): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  886): Waited long enough for: ServiceRecord{168d9fc0 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,E/bt-btm  ( 2491): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311056, SEQNUM=4640, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5446, POWER_SUPPLY_CHARGE_COUNTER=-1087, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,W/bt-btif ( 2491): info:x10
,D/        ( 2491): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/btif_config_util( 2491): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2491): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2491): info:x10
,D/        ( 2491): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/btif_config_util( 2491): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2491): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2491): info:x10
,D/        ( 2491): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
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
,D/btif_config_util( 2491): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2491): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2491): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {a8be9de, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  886): done {a8be9de, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [39ms]
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {22680a31, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  886): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=9763 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [68ms]
,I/GAv4    ( 9763): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9763):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9763):   adb logcat -s GAv4
,W/GAv4    ( 9763): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9763): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9763): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  886): done {22680a31, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [259ms]
,I/ActivityManager(  886): Killing 9550:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_9550/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=239, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310931, SEQNUM=4644, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4841, POWER_SUPPLY_CHARGE_COUNTER=-920, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=239, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311217, SEQNUM=4646, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3227, POWER_SUPPLY_CHARGE_COUNTER=9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=237, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311221, SEQNUM=4648, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=14, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=237, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311792, SEQNUM=4649, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-10, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=237, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310897, SEQNUM=4651, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-52, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/UsageStatsService(  886): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=234, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312043, SEQNUM=4652, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4336, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  886): send {2c4d7516, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [41ms]
,V/AlarmManager(  886): done {2c4d7516, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [106ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=234, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311454, SEQNUM=4656, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=76, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  886): send {a8be9de, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  886): send {1babbe97, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  886): done {a8be9de, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [45ms]
,V/AlarmManager(  886): done {1babbe97, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [51ms]
,I/EventLogService( 8982): Aggregate from 1452246946987 (log), 1452246145436 (data)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=233, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310862, SEQNUM=4659, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=233, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311152, SEQNUM=4661, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-10, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {2d2878f0, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  886): done {2d2878f0, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [28ms]
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311744, SEQNUM=4662, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-22, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  886): send {249dc473, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {226f7c54, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  886): send {1a1610ee, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  886): Prepared write state in 16ms
,V/AlarmManager(  886): done {226f7c54, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [67ms]
,I/ProcessStatsService(  886): Prepared write state in 7ms
,V/AlarmManager(  886): done {249dc473, *alarm*:android.intent.action.TIME_TICK} [93ms]
,V/AlarmManager(  886): done {1a1610ee, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [99ms]
,I/ProcessStatsService(  886): Pruning old procstats: /data/system/procstats/state-2016-01-07-10-42-24.bin
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1758): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311446, SEQNUM=4665, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-167, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 9830): 
D/AndroidRuntime( 9830): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9830): CheckJNI is OFF
D/AndroidRuntime( 9830): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10419 user=-1: uninstall pkg
I/ActivityManager(  886):   Force finishing activity ActivityRecord{209af086 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings(  886): Skipping PackageSetting{2b8c133f com.example.hello/10406} due to missing metadata
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10419 user=0: pkg removed
I/art     ( 3032): Explicit concurrent mark sweep GC freed 13539(2MB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 7MB/12MB, paused 2.300ms total 37.851ms
W/GeofencerStateMachine( 1758): Ignoring removeGeofence because network location is disabled.
I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1424): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1424): run()
I/Decoder ( 1424): createOrResetDecoder
I/art     ( 1576): Explicit concurrent mark sweep GC freed 5406(329KB) AllocSpace objects, 7(353KB) LOS objects, 25% free, 13MB/17MB, paused 495us total 78.470ms
I/ActivityManager(  886): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=9860 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  886): Explicit concurrent mark sweep GC freed 28174(1998KB) AllocSpace objects, 19(3MB) LOS objects, 33% free, 20MB/30MB, paused 1.780ms total 161.815ms
I/art     (  886): WaitForGcToComplete blocked for 75.205ms for cause Explicit
I/ConfigService( 1758): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1424): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1424): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1424): run()
I/StatsUtilsManager( 1424): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1424): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 9860): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  886): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9883 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  886): removeObsoleteFile: deleting file=3_task.xml
I/ContactLocale( 9860): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  886): Explicit concurrent mark sweep GC freed 6279(339KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.995ms total 171.683ms
I/ActivityManager(  886): Killing 9644:com.android.settings/1000 (adj 15): empty #7
D/AndroidRuntime( 9830): Shutting down VM
W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_9644/cgroup.procs: No such file or directory
I/Launcher( 1576): Deferring update until onResume
W/asset   ( 9883): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9883): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9883): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  886): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=9901 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 9901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 8982): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 8982): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 8982): Reading stored module config
D/ChimeraCfgMgr( 8982): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 8982): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 8982): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 8982): App measurement is starting up, version: 8489
I/GMPM-SVC( 8982): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 1758): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1758): Shutting down VM
E/AndroidRuntime( 1758): FATAL EXCEPTION: main
E/AndroidRuntime( 1758): Process: com.google.android.gms.persistent, PID: 1758
E/AndroidRuntime( 1758): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1758): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1758): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1758): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1758): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1758): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1758): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1758): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1758): 	... 9 more
I/Process ( 1758): Sending signal. PID: 1758 SIG: 9
E/DropBoxManagerService(  886): Can't write: system_app_crash
E/DropBoxManagerService(  886): java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
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
I/Icing   ( 8982): doRemovePackageData com.test.thalitest
E/SQLiteDatabase( 8982): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 8982): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 8982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 8982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8982): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 8982): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 8982): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 8982): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 8982): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 8982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8982): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 8982): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 8982): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 8982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 8982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 8982): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 8982): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 8982): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 8982): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 8982): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 8982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 8982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8982): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 8982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 8982): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 8982): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 8982): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/GpsStatusListenerHelper(  886): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@2e937270
D/WifiService(  886): Client connection lost with reason: 4
V/BackupManagerService(  886): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
E/SQLiteLog( 8982): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 8982): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 8982): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 8982): Process: com.google.android.gms, PID: 8982
E/AndroidRuntime( 8982): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 8982): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 8982): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 8982): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 8982): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 8982): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 8982): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 8982): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 8982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8982): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 8982): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 8982): Failed to open Apps corpus file.
E/Icing   ( 8982): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 8982): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
D/ChimeraCfgMgr( 8982): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 8982): Module APK com.google.android.play.games already loaded
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
