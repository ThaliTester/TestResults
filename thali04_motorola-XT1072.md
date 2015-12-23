#### Test 543122980a88295_thali04_motorola-XT1072 Logs


```
--------- beginning of system
E/BackupManagerService(  878): Timeout restoring application @pm@
W/BackupManagerService(  878): Tried to clear data for @pm@ but not found
--------- beginning of main
W/GmsBackupTransport( 1740): Restore processing aborted, no more packages
E/BackupManagerService(  878): Failure getting next package name
E/BackupManagerService(  878): Duplicate finish
,D/AndroidRuntime( 6629): 
D/AndroidRuntime( 6629): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6629): CheckJNI is OFF
D/AndroidRuntime( 6629): Calling main entry com.android.commands.am.Am
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6648 uid=10403 gids={50403, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6629): Shutting down VM
I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 22.503ms
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.818ms
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 22.756ms
I/art     (  878): Explicit concurrent mark sweep GC freed 42443(2MB) AllocSpace objects, 2(214KB) LOS objects, 33% free, 20MB/30MB, paused 1.526ms total 135.203ms
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6648): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6648): Time to load native libraries: 5 ms (timestamps 5488-5493)
,I/LibraryLoader( 6648): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6648): Binding Chromium to main looper Looper (main, tid 1) {2d9e4624}
I/LibraryLoader( 6648): Expected native library version number "",actual native library version number ""
,I/chromium( 6648): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6648): Initializing chromium process, singleProcess=true
,W/art     ( 6648): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6648): ApplicationContext is null in ApplicationStatus
,W/chromium( 6648): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6648): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6648): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6648): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6648): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6648): Local Branch: 
I/Adreno-EGL( 6648): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6648): Local Patches: NONE
I/Adreno-EGL( 6648): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  878): Activity pause timeout for ActivityRecord{1d630c88 u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  878): Message: 20
D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6f4cff:true
,W/art     ( 6648): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6648): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6648): CordovaWebView is running on device made by: motorola
W/art     ( 6648): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6648): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6648): Render dirty regions requested: true
,D/Atlas   ( 6648): Validating map...
,W/chromium( 6648): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6648): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6648): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,1275
I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +1s23ms (total +1s275ms)
,W/IInputConnectionWrapper( 6648): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6648): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6648): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6648): Cannot call determinedVisibility() - never saw a connection for the pid: 6648
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,D/JsMessageQueue( 6648): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6648): JniHelper::setJavaVM(0xb82d7310), pthread_self() = -1201241208
,D/JX-Cordova( 6648): jxcore cordova android initializing
,W/jxcore-log( 6648): Initializing JXcore engine
W/jxcore-log( 6648): JXcore engine is ready
,W/jxcore-log( 6648): Starting JXcore engine
,W/.test.thalitest( 6648): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10403 path="socket:[5646]" dev="sockfs" ino=5646 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6648): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10403 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6648): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10403 path="socket:[9403]" dev="sockfs" ino=9403 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6648): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10403 path="socket:[28125]" dev="sockfs" ino=28125 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6648): Platform android
W/jxcore-log( 6648): 
W/jxcore-log( 6648): Process ARCH arm
W/jxcore-log( 6648): 
,I/jxcore-log( 6648): JXcore Cordova bridge is ready!
I/jxcore-log( 6648): 
,W/jxcore-log( 6648): JXcore engine is started
,I/chromium( 6648): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6648): Toggling radios to true
I/jxcore-log( 6648): 
,D/BluetoothAdapter( 6648): enable(): BT is already enabled..!
,D/WifiService(  878): New client listening to asynchronous messages
,D/WifiService(  878): setWifiEnabled: true pid=6648, uid=10403
E/WifiService(  878): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6648): Radios toggled
I/jxcore-log( 6648): 
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6648): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6648): 
,I/jxcore-log( 6648): Perf Test app loaded loaded
I/jxcore-log( 6648): 
,I/jxcore-log( 6648): check test folder
I/jxcore-log( 6648): 
I/jxcore-log( 6648): found test : ./testFindPeers.js
I/jxcore-log( 6648): 
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  306):  STA Disconnected !!
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/Tethering(  878): InitialState.processMessage what=4
,I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
,I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  306): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  878): WifiStateMachine: Leaving Connected state
,W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  306): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  878): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/Tethering(  878):  0
,D/Tethering(  878): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
D/WifiP2pService(  878): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/jxcore-log( 6648): found test : ./testSendData.js
I/jxcore-log( 6648): 
,D/CommandListener(  304): Clearing all IP addresses on wlan0
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
,D/TCMD    (  483): Listening for incoming client connection request
,V/NativeCrypto( 1740): Read error: ssl=0xb8610c48: I/O error during system call, Connection timed out
,V/NativeCrypto( 1740): SSL shutdown failed: ssl=0xb8610c48: I/O error during system call, Broken pipe
,D/ConnectivityService(  878): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/jxcore-log( 6648): found test : ./testSendData2.js
I/jxcore-log( 6648): 
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6715 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  878): connected time updated 121182
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  878): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  878): ConnectModeState: Network connection lost 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  304): Clearing all IP addresses on wlan0
D/ConnectivityService(  878): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524292
D/Nat464Xlat(  878): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  878): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Disconnected - quitting
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  878): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  878): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/chromium( 6648): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  878): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
W/ResourcesManager( 6715): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/PhenotypeConfigurator( 1740): Scheduling Phenotype for one-off execution 7433 seconds from now (1450834071860)
,D/GetConfigurationSnapshotOperation( 1740): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Babel_SMS( 6715): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6715): MmsConfig.loadMmsSettings
I/Babel_SMS( 6715): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6715): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6715): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6715): MmsConfig.loadFromResources
,E/Babel_SMS( 6715): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6715): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
,D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  306): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1408): wlan0: Trying to associate with SSID 'NG700'
,D/WifiMonitor(  878): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1408): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  306): Event received = Trying to associate with
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  878): [1,450,834,071,952 ms] noteScanEnd no scan source
E/WifiStateMachine(  878): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@28198e98 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/PhenotypeFlagCommitter( 1740): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1740): Using platform SSLCertificateSocketFactory
,W/Settings( 6715): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6715): startup - clean
,I/Babel   ( 6715): deleted: false for 0
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
I/wpa_supplicant( 1408): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  306): Event received = Associated with c0:ff:d4
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  878): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6765 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6765): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,W/AudioCapabilities( 6715): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6715): Unsupported mime video/mpeg2
,I/ActivityManager(  878): Killing 6296:android.process.acore/u0a7 (adj 15): empty #7
,I/VideoCapabilities( 6715): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_6296/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Killing 6503:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_6503/cgroup.procs: No such file or directory
,I/vclib   ( 6715): onServiceConnected
,W/Babel   ( 6715): Attempted to change video mute state without an active call.
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1740): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/global frequency( 2629): no tags to log
,D/Checkin ( 2629): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2629): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 55757(3MB) AllocSpace objects, 35(1224KB) LOS objects, 39% free, 7MB/12MB, paused 1.115ms total 54.666ms
,I/art     ( 2629): Explicit concurrent mark sweep GC freed 14644(816KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.032ms total 83.049ms
,D/BSUtils ( 2629): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2629): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2629): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6799 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1461): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/art     (  878): Explicit concurrent mark sweep GC freed 34852(1773KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.442ms total 135.730ms
,I/MusicStore( 6799): Database version: 120
,D/BSUtils ( 2629): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2629): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2629): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 4311(188KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 720us total 28.764ms
,D/BSUtils ( 2629): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/BSUtils ( 2629): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BSUtils ( 2629): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/global frequency( 2629): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2629): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2629): BcsDSCheckin.logProperties: BL State from property is null or empty
D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Checkin ( 2629): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2629): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1408): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  306): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306):  STA Connected !!
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/MDMCTBK (  306): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  306): get_freq !!, resp=2412
I/MDMCTBK (  306): get_freq !!, Strip data
I/MDMCTBK (  306): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1204294328
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
E/WifiStateMachine(  878): Network connection established
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,W/ResourcesManager( 6799): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6799): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  878): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  878): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  878): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  878): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  304): Setting iface cfg
,E/WifiStateMachine(  878): Start Dhcp Watchdog 2
,D/OtaApp  ( 2629): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2629): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/PollingManager( 2629): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/PollingManager( 2629): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend false
,D/OtaApp  ( 2629): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  878): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  878): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ba020ea target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ba020ea target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 2629): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2629): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2629): Registering with Alarm Manager to restart CCE
,V/JNIHelp ( 6799): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CCE     ( 2629): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2629): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2629): [debug] > CusSM.onRadioDown
,I/global frequency( 2629): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2629): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/ActivityThread( 6799): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6799): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2969ba80: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6799): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6799): GMSCore installation verified
,I/ConfigStore( 6799): Config Database version: 1
,I/MediaRouter( 6799): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6799): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/DHCPCD  ( 6833): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6833): version 5.5.6 starting
,E/DHCPCD  ( 6833): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6833): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6833): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6844 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DHCPCD  ( 6833): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6833): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6833): wlan0: sending REQUEST (xid 0xba231165), next in 4.96 seconds
,V/AlarmManager(  878): send {cfa0e69, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/GHttpClientFactory( 6799): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6799): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 6441:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_6441/cgroup.procs: No such file or directory
,V/Mms     ( 6844): mnc/mcc: 
,V/Mms     ( 6844): tag: int value: recipientLimit - 20
,V/Mms     ( 6844): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6844): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6844): tag: int value: maxSubjectLength - 80
V/Mms     ( 6844): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6844): tag: bool value: enableGroupMms - false
,V/Mms     ( 6844):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6871 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6531:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_6531/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6871): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6871): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6871): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  878): Killing 6715:com.google.android.talk/u0a70 (adj 15): empty #7
,I/iu.UploadsManager( 1956): num queued entries: 0
,I/iu.UploadsManager( 1956): num updated entries: 0
,I/iu.SyncManager( 1956): NEXT; no task
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6715/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6889 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6909 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6765:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_6765/cgroup.procs: No such file or directory
,W/ResourcesManager( 6909): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6648): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6648): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6648): BLE supported!!
I/jxcore-log( 6648): 
,I/Babel_SMS( 6909): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6909): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6909): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6909): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6909): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6909): MmsConfig.loadFromResources
E/Babel_SMS( 6909): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6909): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/DHCPCD  ( 6833): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6833): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6833): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/DHCPCD  ( 6833): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  483): NL - ignore NL message, type = 20
D/TCMD    (  483): Listening for incoming client connection request
D/DHCPCD  ( 6833): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6833): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6833): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6909): startup - clean
,I/Babel   ( 6909): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6965 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6909): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6909): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6909): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6909): onServiceConnected
,W/Babel   ( 6909): Attempted to change video mute state without an active call.
,I/Babel   ( 6909): connection state changed from UNKNOWN to DISCONNECTED
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  878): WifiStateMachine DHCP successful
I/ActivityManager(  878): Killing 6799:com.google.android.music:main/u0a80 (adj 15): empty #7
E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  878): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_6799/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  878): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  878): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  878): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  878): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  878): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  878): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  878): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  878): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  878): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878):    accepting network in place of null
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  878): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  878): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450833994628 min interval config: 0 actual interval: 82553
,I/CheckinService( 1956): Checking schedule, now: 1450834077188 next: 1450834024608
I/CheckinService( 1956): active receiver: enabled
,I/CheckinService( 1956): Preparing to send checkin request
I/EventLogService( 1956): Accumulating logs since 1450833991239
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 01:27:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450834077277], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450834077257]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Validated
,D/ConnectivityService(  878): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524290
,I/art     (  878): Explicit concurrent mark sweep GC freed 21725(1104KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.599ms total 123.966ms
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/CheckinRequestBuilder( 1956): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6965): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6965):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6965):   adb logcat -s GAv4
,W/GAv4    ( 6965): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6965): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6965): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7004 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7004): VM with version 2.1.0 has multidex support
I/MultiDex( 7004): install
I/MultiDex( 7004): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7004): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7004): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7004): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28d537a1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7004): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7004): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7004): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/WebViewFactory( 6965): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6965): Time to load native libraries: 2 ms (timestamps 7914-7916)
I/LibraryLoader( 6965): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6965): Binding Chromium to main looper Looper (main, tid 1) {3d6a4b11}
I/LibraryLoader( 6965): Expected native library version number "",actual native library version number ""
I/chromium( 6965): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6965): Initializing chromium process, singleProcess=true
W/art     ( 6965): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6965): ApplicationContext is null in ApplicationStatus
,W/chromium( 6965): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6965): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6965): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6965): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6965): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6965): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6965): Local Branch: 
I/Adreno-EGL( 6965): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6965): Local Patches: NONE
I/Adreno-EGL( 6965): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/NativeLibraryUtils( 7004): Install completed successfully. count=14 extracted=0
,I/NSApplication( 6965): Starting up...
,W/AudioManagerAndroid( 6965): Requires BLUETOOTH permission
D/WVCdm   (  310): Instantiating CDM.
I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7064 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xb1428960
D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7e68c40, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e5b008, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f59dc0, idLength=0xb5512730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  310): hlos api version =  9
,D/DrmWidevineDash(  310): tz api version =  8
,D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  310): PrepareKeyRequest: nonce=2119918443
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e38cb8
D/DrmWidevineDash(  310): message_length=1591, signature=0xb7e392f8, signature_length=3041994516
,D/ConnectivityService(  878): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7085 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6844:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.323ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.626ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.706ms
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_6844/cgroup.procs: No such file or directory
,W/ResourcesManager( 7085): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7109 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
,D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7132 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6889:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524295
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xbeadd4e0
D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7e937f8, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e5b008, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f59e00, idLength=0xb5512730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  310): PrepareKeyRequest: nonce=1567539626
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e38d30
D/DrmWidevineDash(  310): message_length=1626, signature=0xb7e86be8, signature_length=3041994516
,I/ContactLocale( 7109): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 6871:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
,D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,V/AlarmManager(  878): send {102a20f7, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_6889/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_6871/cgroup.procs: No such file or directory
,I/dex2oat ( 7157): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/MusicStore( 7132): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7132): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/dex2oat ( 7157): dex2oat took 107.617ms (threads: 4)
,I/Adreno-EGL( 7004): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7004): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7004): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7004): Local Branch: 
I/Adreno-EGL( 7004): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7004): Local Patches: NONE
I/Adreno-EGL( 7004): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7132): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7132): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7132): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7132): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Adreno-EGL( 7004): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7004): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7004): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7004): Local Branch: 
I/Adreno-EGL( 7004): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7004): Local Patches: NONE
I/Adreno-EGL( 7004): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/JNIHelp ( 7132): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7132): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7132): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2969ba80: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/Adreno-EGL( 7004): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7004): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7004): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7004): Local Branch: 
I/Adreno-EGL( 7004): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7004): Local Patches: NONE
I/Adreno-EGL( 7004): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
I/ProviderInstaller( 7132): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7132): GMSCore installation verified
,I/ConfigStore( 7132): Config Database version: 1
,I/Adreno-EGL( 7004): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7004): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7004): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7004): Local Branch: 
I/Adreno-EGL( 7004): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7004): Local Patches: NONE
I/Adreno-EGL( 7004): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/MediaRouter( 7132): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7132): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7132): type=WIFI subType= reason=null isConnected=true
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/NetworkMonitor( 7132): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7181 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7132): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7132): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 6909:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7181): mnc/mcc: 
V/Mms     ( 7181): tag: int value: recipientLimit - 20
,V/Mms     ( 7181): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7181): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7181): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7181): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7181): tag: bool value: enableGroupMms - false
V/Mms     ( 7181):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6909/cgroup.procs: No such file or directory
,I/CheckinTask( 1956): Sending checkin request (9510 bytes)
,W/ResourcesManager( 7181): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7209 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6965:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7209): Register our PhoneStateListener
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_6965/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7209): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7209): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 7064:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7064/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450833994628 min interval config: 0 actual interval: 85427
,I/iu.Environment( 1956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1956): num queued entries: 0
I/iu.UploadsManager( 1956): num updated entries: 0
,I/iu.SyncManager( 1956): NEXT; no task
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7232 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2629): now: 200303 ,futureTime: 9223372036854775807
,D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2629): now: 200303 ,futureTime: 9223372036854775807
D/PollingManager( 2629): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2629): now: 200303 ,futureTime: 9223372036854775807
D/OtaApp  ( 2629): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/NetworkMonitor( 7132): type=WIFI subType= reason=null isConnected=true
,I/CheckinRequestBuilder( 1956): Checkin reason type: 8 attempt count: 1
,I/art     (  878): Explicit concurrent mark sweep GC freed 13521(648KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.585ms total 132.423ms
,D/Central_PollingManager( 1461): now: 200412 ,futureTime: 86474486
D/Central_PollingManager( 1461): Polling alarm set to expire at: 86474486 Current Time: 200412
,D/OtaApp  ( 2629): [debug] > PollingManagerService, now: 200411 ,futureTime: 20244574
D/OtaApp  ( 2629): [debug] > Polling alarm set to expire at: 20244574 Current Time: 200413
,D/OtaApp  ( 2629): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2629): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2629): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2629): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2629): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiProvisionService( 2629): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2629): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2629): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2629): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,D/OtaApp  ( 2629): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/CCE     ( 2629): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2629): createDeviceIdOrLogin update_device
D/Checkin ( 2629): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2629): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2629): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2629): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2629): createDeviceIdOrLogin update_device
D/Checkin ( 2629): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2629): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2629): set mOutstandingReq to true.
I/ Nonce  ( 2629):  Nonce getNonce 
I/ Nonce  ( 2629):  Nonce Request 
I/ Nonce  ( 2629):  Nonce execute Request 
,D/MMApiWebService( 2629): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2629): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2629): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2629): createDeviceIdOrLogin update_device
D/Checkin ( 2629): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2629): Not proxy app, so login/provision not allowed
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 4060(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 675us total 30.811ms
,D/MMApiWebService( 2629): generating token using payload instead of using session token
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/art     ( 2629): Explicit concurrent mark sweep GC freed 12758(741KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 2.468ms total 62.410ms
I/CheckinService( 1956): Checking schedule, now: 1450834080561 next: 1451435217549
,I/CheckinService( 1956): active receiver: disabled
,D/ Nonce  ( 2629):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/CheckinService( 1956): Checking schedule, now: 1450834080584 next: 1451435217549
I/CheckinService( 1956): active receiver: disabled
I/MMApiWSBase( 2629): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2629): publish the event [tag = MOT_CCE event name = LOG]
,D/CheckinService( 1956): Recording last checkin time for package unspecified as 1450834080588
,I/ActivityManager(  878): Killing 7109:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  878): Killing 7085:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7109/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7085/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7268 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7132:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7132/cgroup.procs: No such file or directory
,W/ResourcesManager( 7268): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7268): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7268): MmsConfig.loadMmsSettings
I/Babel_SMS( 7268): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7268): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7268): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7268): MmsConfig.loadFromResources
E/Babel_SMS( 7268): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7268): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7268): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7268): startup - clean
,I/Babel   ( 7268): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7295 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7268): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7268): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7268): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7268): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7268): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7268): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7268): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7295): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7268): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7295): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7295): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7295):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7295):   adb logcat -s GAv4
,I/vclib   ( 7268): onServiceConnected
W/Babel   ( 7268): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7295): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7295): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ Nonce  ( 2629):  Nonce Reponse 
D/        ( 2629): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7d11d2b6-eeaa-44f1-9cf7-06b418879709"}
D/MMApiWSBase( 2629): doRequest(): /v1/gdi/nonce.json resp length: 61
W/GAv4    ( 7295): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/ Nonce  ( 2629):  Nonce Handle Reponse 
D/MMApiProvisionService( 2629): mOutstandingReq set to false
,W/GAv4    ( 7295): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7268): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 7181:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7295): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/MMApiProvisionService( 2629):  pTime 1450832528498 sExp 172742 cTime 1450834081557 tTime 1451005270498
D/MMApiProvisionService( 2629):  No login Required 
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7181/cgroup.procs: No such file or directory
,I/WebViewFactory( 7295): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7295): Time to load native libraries: 2 ms (timestamps 1924-1926)
I/LibraryLoader( 7295): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7295): Binding Chromium to main looper Looper (main, tid 1) {3d6a4b11}
I/LibraryLoader( 7295): Expected native library version number "",actual native library version number ""
I/chromium( 7295): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7295): Initializing chromium process, singleProcess=true
,W/art     ( 7295): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7295): ApplicationContext is null in ApplicationStatus
,W/chromium( 7295): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7295): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7295): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7295): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7295): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7295): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7295): Local Branch: 
I/Adreno-EGL( 7295): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7295): Local Patches: NONE
I/Adreno-EGL( 7295): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7295): Requires BLUETOOTH permission
,I/NSApplication( 7295): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7364 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7209:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7209/cgroup.procs: No such file or directory
,W/DataUsage( 2629): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2629): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7383 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7232:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7232/cgroup.procs: No such file or directory
,I/art     (  878): Explicit concurrent mark sweep GC freed 9359(467KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.664ms total 129.177ms
,W/ResourcesManager( 7383): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7406 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7295:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7406): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 7268:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2629): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7295/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7268/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2629): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2629): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2629): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2629): onServiceConnected()
D/GetNotificationsWS( 2629): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2629): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2629): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7436 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 23.991ms
,W/ResourcesManager( 7436): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 19.877ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 19.996ms
,I/ActivityManager(  878): Killing 7004:com.google.android.gms.unstable/u0a16 (adj 13): empty #7
,V/AlarmManager(  878): done {cfa0e69, *walarm*:com.google.android.intent.action.SEND_IDLE} [7467ms]
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7454 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_7004/cgroup.procs: No such file or directory
,W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312434, SEQNUM=4452, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18529, POWER_SUPPLY_CHARGE_COUNTER=-625, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/WearableService( 1740): callingUid 10016, callindPid: 1740
,D/LocationInitializer( 1956): Restart initialization of location
,E/MDM     ( 1740): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  878): done {102a20f7, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4597ms]
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7481 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1740): No location to return for getLastLocation()
,W/FusedLocationProvider( 1740): location=null
,I/MusicStore( 7481): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7481): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7481): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7481): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7481): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7481): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7481): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7481): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7481): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2969ba80: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7481): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7481): GMSCore installation verified
,I/ConfigStore( 7481): Config Database version: 1
,I/MediaRouter( 7481): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7481): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7481): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7481): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7520 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7481): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7481): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 7364:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     ( 5732): Explicit concurrent mark sweep GC freed 2181(97KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 4.499ms total 65.947ms
,V/Mms     ( 7520): mnc/mcc: 
,V/Mms     ( 7520): tag: int value: recipientLimit - 20
V/Mms     ( 7520): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7520): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7520): tag: int value: maxSubjectLength - 80
V/Mms     ( 7520): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7520): tag: bool value: enableGroupMms - false
V/Mms     ( 7520):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7364/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7549 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7549): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7549): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7520): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7569 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/MultiDex( 7549): VM with version 2.1.0 has multidex support
,I/MultiDex( 7549): install
,I/MultiDex( 7549): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7549): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 7569): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7569): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7569): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 7383:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/ActivityThread( 7549): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7549): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28d537a1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7549): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7383/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450834080588 min interval config: 0 actual interval: 3683
I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450834080588 min interval config: 0 actual interval: 3686
,I/art     ( 7549): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7549): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/CheckinService( 1956): Checking schedule, now: 1450834084315 next: 1450834110549
I/CheckinService( 1956): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7592 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1956): Checking schedule, now: 1450834084367 next: 1450834110549
I/CheckinService( 1956): active receiver: disabled
,I/ActivityManager(  878): Killing 7406:android.process.acore/u0a7 (adj 15): empty #7
,D/NativeLibraryUtils( 7549): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7406/cgroup.procs: No such file or directory
,W/ResourcesManager( 7592): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7592): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7592): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7592): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7592): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7592): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7592): MmsConfig.loadFromResources
,E/Babel_SMS( 7592): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7592): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7592): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7592): startup - clean
,I/Babel   ( 7592): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7619 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7436:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_7436/cgroup.procs: No such file or directory
,W/VideoCapabilities( 7592): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7592): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7592): Unsupported mime video/mpeg2
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/VideoCapabilities( 7592): Unsupported profile 4 for video/mp4v-es
,W/ContextImpl( 7619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7619): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7619):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7619):   adb logcat -s GAv4
,W/VideoCapabilities( 7592): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7592): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 7592): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7592): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7619): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 7592): onServiceConnected
,W/Babel   ( 7592): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7619): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7619): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7592): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 7481:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7481/cgroup.procs: No such file or directory
,I/art     (  878): Explicit concurrent mark sweep GC freed 12193(604KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.485ms total 126.327ms
,I/WebViewFactory( 7619): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7619): Time to load native libraries: 1 ms (timestamps 5754-5755)
,I/LibraryLoader( 7619): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7619): Binding Chromium to main looper Looper (main, tid 1) {3d6a4b11}
I/LibraryLoader( 7619): Expected native library version number "",actual native library version number ""
I/chromium( 7619): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7619): Initializing chromium process, singleProcess=true
,W/art     ( 7619): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7619): ApplicationContext is null in ApplicationStatus
,W/chromium( 7619): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7619): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7619): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7619): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7619): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7619): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7619): Local Branch: 
I/Adreno-EGL( 7619): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7619): Local Patches: NONE
I/Adreno-EGL( 7619): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7619): Starting up...
,W/AudioManagerAndroid( 7619): Requires BLUETOOTH permission
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7690 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7520:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7520/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7709 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7569:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7569/cgroup.procs: No such file or directory
,W/ResourcesManager( 7709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7729 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7549:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/ActivityManager(  878): Killing 7454:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,I/ContactLocale( 7729): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_7549/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2629): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7454/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2629): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2629): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2629): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2629): onServiceConnected()
D/GetNotificationsWS( 2629): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 2629): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2629): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2629): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2629): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2629): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2629): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2629): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2629): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2629): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2629): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2629): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2629): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2629): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
W/IInputConnectionWrapper( 6648): showStatusIcon on inactive InputConnection
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7766 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/LaunchCheckinHandler(  878): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,133
,I/art     (  324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.192ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 21.042ms
,D/PhoneMonitor( 7766): Register our PhoneStateListener
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.901ms
,V/SetupWizard( 7766): Connected to Gservices successfully
,I/ActivityManager(  878): Killing 7619:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7619/cgroup.procs: No such file or directory
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7791 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@8f94a32
,I/GCoreNlp( 1740): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1570): Deferring update until onResume
,E/MDM     ( 1740): [220] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1956): Restart initialization of location
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1740): No location to return for getLastLocation()
,W/FusedLocationProvider( 1740): location=null
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  878): Killing 7690:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7690/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7826 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7855 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7709:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7709/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7878 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 7878): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7878): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7592): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7592): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1956): Null package name or gms related package.  Ignoreing.
,V/JNIHelp ( 7592): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1dd7918e new=com.google.android.velvet.VelvetApplication@1dd7918e
I/UpdateIcingCorporaServi( 7826): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1956): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7913 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 7592): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7592): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7913): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7826): UpdateCorporaTask done [took 152 ms] updated apps [took 152 ms] 
,I/ActivityManager(  878): Killing 7791:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     ( 1956): Explicit concurrent mark sweep GC freed 47732(2MB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 15MB/25MB, paused 1.278ms total 120.668ms
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7791/cgroup.procs: No such file or directory
,I/art     (  878): Explicit concurrent mark sweep GC freed 17299(875KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.483ms total 116.878ms
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7939 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7766:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7766/cgroup.procs: No such file or directory
,D/Finsky  ( 7939): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7939): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7939): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7939): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7939): Skipping gmscore version check
D/Finsky  ( 7939): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7939): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  878): Killing 7855:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_7855/cgroup.procs: No such file or directory
,D/Finsky  ( 7939): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7939): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/Icing   ( 1956): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1956): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/TaskPersister(  878): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  878): Killing 7878:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_7878/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Killing 7592:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7592/cgroup.procs: No such file or directory
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312335, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-762, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1740): disconnect managed GoogleApiClient
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {2c66789f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  878): send {d0e3a3f, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [81ms]
V/AlarmManager(  878): done {2c66789f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [82ms]
,V/AlarmManager(  878): done {d0e3a3f, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [88ms]
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1450834080588 min interval config: 0 actual interval: 46129
,I/CheckinService( 1956): Checking schedule, now: 1450834126735 next: 1450834110549
I/CheckinService( 1956): active receiver: enabled
,I/CheckinService( 1956): Preparing to send checkin request
I/EventLogService( 1956): Accumulating logs since 1450834077349
,I/CheckinRequestBuilder( 1956): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8009 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8009): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8009): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8009): VM with version 2.1.0 has multidex support
I/MultiDex( 8009): install
I/MultiDex( 8009): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8009): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8009): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8009): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28d537a1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8009): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1740): callingUid 10016, callindPid: 1740
,E/MDM     ( 1740): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1956): Restart initialization of location
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1740): No location to return for getLastLocation()
,W/FusedLocationProvider( 1740): location=null
,I/art     ( 8009): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 8009): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8009): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  310): Instantiating CDM.
,I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xb5512960
,D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7e68610, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e5b008, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f59de0, idLength=0xb132a730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  310): PrepareKeyRequest: nonce=2170869402
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f0e548
,D/DrmWidevineDash(  310): message_length=1591, signature=0xb7e86bc8, signature_length=2972886804
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  310): CdmEngine::CloseSession
,D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  310): Service_Initialize: starts!
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5037000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xb5612960
D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7f0e7b0, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e3c150, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f59e00, idLength=0xb1428730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  310): PrepareKeyRequest: nonce=1852190553
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e86588
D/DrmWidevineDash(  310): message_length=1626, signature=0xb7e86be8, signature_length=2973927188
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8053): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8053): dex2oat took 95.146ms (threads: 4)
,I/Adreno-EGL( 8009): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8009): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8009): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8009): Local Branch: 
I/Adreno-EGL( 8009): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8009): Local Patches: NONE
I/Adreno-EGL( 8009): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8009): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8009): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8009): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8009): Local Branch: 
I/Adreno-EGL( 8009): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8009): Local Patches: NONE
I/Adreno-EGL( 8009): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8009): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8009): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8009): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8009): Local Branch: 
I/Adreno-EGL( 8009): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8009): Local Patches: NONE
I/Adreno-EGL( 8009): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8009): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8009): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8009): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8009): Local Branch: 
I/Adreno-EGL( 8009): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8009): Local Patches: NONE
I/Adreno-EGL( 8009): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Sending checkin request (9505 bytes)
,I/CheckinRequestBuilder( 1956): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1956): Checking schedule, now: 1450834130913 next: 1451435267904
I/CheckinService( 1956): active receiver: disabled
,D/CheckinService( 1956): Recording last checkin time for package unspecified as 1450834130923
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8077 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8077): Register our PhoneStateListener
,V/SetupWizard( 8077): Connected to Gservices successfully
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Killing 7729:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  878): Killing 7826:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7729/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_7826/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8107 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1740): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1570): Deferring update until onResume
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1f55be79
,I/art     ( 1740): Explicit concurrent mark sweep GC freed 90662(5MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 15MB/25MB, paused 1.296ms total 121.727ms
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1106eded)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ebfb422)
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24ce3eb3)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@345d6c70)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11717be9)
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8137 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8154 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7913:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.156ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 19.396ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20ms
,I/ActivityManager(  878): Killing 7939:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7913/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_7939/cgroup.procs: No such file or directory
,I/art     (  878): Explicit concurrent mark sweep GC freed 22155(1172KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.316ms total 121.885ms
,W/ResourcesManager( 8154): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8154): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8154): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8154): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8154): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8154): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8154): MmsConfig.loadFromResources
,E/Babel_SMS( 8154): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8154): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8154): startup - clean
,I/Babel   ( 8154): deleted: false for 0
,I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8187 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8154): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8154): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8154): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8154): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8154): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 8187): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8212 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 8077:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_8077/cgroup.procs: No such file or directory
,I/vclib   ( 8154): onServiceConnected
,W/Babel   ( 8154): Attempted to change video mute state without an active call.
,W/asset   ( 8212): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8212): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8212): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8212): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 8154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1956): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1dd7918e new=com.google.android.velvet.VelvetApplication@1dd7918e
,I/UpdateIcingCorporaServi( 8107): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1956): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8240 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 8154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8154): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8240): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8107): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8267 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8009:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_8009/cgroup.procs: No such file or directory
,D/Finsky  ( 8267): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8267): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8267): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8267): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8267): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8267): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8267): Skipping gmscore version check
,D/Finsky  ( 8267): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8267): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  878): Killing 8137:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_8137/cgroup.procs: No such file or directory
,I/Icing   ( 1956): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1956): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 8212:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_8212/cgroup.procs: No such file or directory
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  878): Killing 8154:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_8154/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1740): onCreate
,I/ConfigService( 1740): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311951, SEQNUM=4497, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-957, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1516e7e8, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  878): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8333 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [91ms]
,I/GAv4    ( 8333): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8333):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8333):   adb logcat -s GAv4
,W/GAv4    ( 8333): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8333): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8333): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  878): Killing 8107:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,V/AlarmManager(  878): done {1516e7e8, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [278ms]
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_8107/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6648): Connected to the server!
I/jxcore-log( 6648): 
,I/chromium( 6648): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  878): send {3ad99e01, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  878): done {3ad99e01, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6648): --- start :testSendData2.js---
I/jxcore-log( 6648): 
,E/jxcore  ( 6648): Error!: self.tests[testData.testName] is not a constructor
E/jxcore  ( 6648): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 6648): [INFO:CONSOLE(63)] "logCallback --- start :testSendData2.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312116, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1447, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6648): Connected to the server!
I/jxcore-log( 6648): 
,I/chromium( 6648): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6648): teardown
I/jxcore-log( 6648): 
,E/jxcore  ( 6648): Error!: self.currentTest is undefined
E/jxcore  ( 6648): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:159:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 6648): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6648): Connected to the server!
I/jxcore-log( 6648): 
,I/chromium( 6648): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {2da6216b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  878): send {1292c4a6, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  878): done {2da6216b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [25ms]
,V/AlarmManager(  878): done {1292c4a6, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [36ms]
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/EventLogService( 1956): Aggregate from 1450834126760 (log), 1450832523037 (data)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {10582283, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  878): done {10582283, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [83ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {45ccc00, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  878): done {45ccc00, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [19ms]
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  878): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {3ad99e01, *walarm*:android.content.syncmanager.SYNC_ALARM}
,I/ProcessStatsService(  878): Prepared write state in 12ms
,V/AlarmManager(  878): done {3ad99e01, *walarm*:android.content.syncmanager.SYNC_ALARM} [94ms]
,I/ProcessStatsService(  878): Prepared write state in 8ms
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [123ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=0, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311709, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-422, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=0, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311714, SEQNUM=4513, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-422, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2492): Disconnected process message: 10, size: 0
,V/AlarmManager(  878): send {2da6216b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  878): send {2aff8642, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  878): send {8a3c27e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  878): done {2da6216b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [20ms]
,V/AlarmManager(  878): done {2aff8642, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [33ms]
,V/AlarmManager(  878): done {8a3c27e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [53ms]
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1740): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1740): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1740): Server returned 404
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {15cc9255, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {18e7fa1d, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  878): send {18688492, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  878): send {17d11e63, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  878): done {15cc9255, *alarm*:android.intent.action.TIME_TICK} [52ms]
,V/AlarmManager(  878): done {18e7fa1d, *walarm*:com.motorola.ccc.cce.alarmintent} [94ms]
,V/AlarmManager(  878): done {18688492, *walarm*:com.motorola.ccc.cce.alarmintent} [108ms]
,V/AlarmManager(  878): done {17d11e63, *walarm*:com.motorola.ccc.cce.alarmintent} [126ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8453): 
D/AndroidRuntime( 8453): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8453): CheckJNI is OFF
D/AndroidRuntime( 8453): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10403 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 6648:com.test.thalitest/u0a403 (adj 9): stop com.test.thalitest
I/WindowState(  878): WIN DEATH: Window{18fb73ef u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  878): Skipping PackageSetting{3bb2b7e5 com.example.hello/10377} due to missing metadata
D/WifiService(  878): Client connection lost with reason: 4
I/ActivityManager(  878):   Force finishing activity ActivityRecord{1d630c88 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  878): Spurious death for ProcessRecord{3ede4a60 6648:com.test.thalitest/u0a403}, curProc for 6648: null
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10403 user=0: pkg removed
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
W/GeofencerStateMachine( 1740): Ignoring removeGeofence because network location is disabled.
I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
I/art     ( 3057): Explicit concurrent mark sweep GC freed 11246(2MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 7MB/12MB, paused 919us total 76.057ms
D/VoicemailCleanupService( 8187): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
I/Decoder ( 1416): createOrResetDecoder
I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8485 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1570): Explicit concurrent mark sweep GC freed 4963(306KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 765us total 129.670ms
I/art     (  878): Explicit concurrent mark sweep GC freed 33258(2039KB) AllocSpace objects, 11(263KB) LOS objects, 33% free, 20MB/30MB, paused 3.534ms total 169.928ms
I/art     (  878): WaitForGcToComplete blocked for 42.091ms for cause Explicit
I/art     ( 1956): Explicit concurrent mark sweep GC freed 885(35KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 951us total 178.667ms
I/ConfigService( 1740): onCreate
W/asset   ( 8485): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8485): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8485): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8485): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8509 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  878): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
I/ActivityManager(  878): Killing 8240:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
I/art     (  878): Explicit concurrent mark sweep GC freed 7410(404KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.775ms total 219.657ms
W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_8240/cgroup.procs: No such file or directory
I/Launcher( 1570): Deferring update until onResume
W/ContextImpl( 8509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1956): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1956): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1956): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1956): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1956): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1956): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1740): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1740): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/AndroidRuntime( 8453): Shutting down VM
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1956): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1956): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1956): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1956): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8531 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1956): doRemovePackageData com.test.thalitest
W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1dd7918e new=com.google.android.velvet.VelvetApplication@1dd7918e
I/ActivityManager(  878): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8557 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8585 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8531): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  878): Killing 8267:com.android.vending/u0a32 (adj 15): empty #7
W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_8267/cgroup.procs: No such file or directory
E/SQLiteLog( 8531): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 8531): Exception thrown from onTableChanged
E/AppDataSearchHelper( 8531): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8531): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 8531): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 8531): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchHelper( 8531): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 8531): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 8531): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 8531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 8531): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 8531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 8531): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8531): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 8531): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 8531): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 8531): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 8531): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 8531): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 8531): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 8531): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 8531): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 8531): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 8531): 	... 16 more
W/AppDataSearchHelper( 8531): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 8531): UpdateCorporaTask done [took 244 ms] updated apps [took 244 ms] 
I/ActivityManager(  878): Killing 8333:com.google.android.deskclock/u0a55 (adj 15): empty #7
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
