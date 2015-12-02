#### Test 5198634075bb434_thali04_motorola-XT1072 Logs


```
--------- beginning of main
E/global frequency( 2570): no tags to log
D/Checkin ( 2570): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2570): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2570): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2570): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1470): Explicit concurrent mark sweep GC freed 55600(3MB) AllocSpace objects, 37(1241KB) LOS objects, 39% free, 7MB/12MB, paused 834us total 48.029ms
D/BSUtils ( 2570): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2570): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2570): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2570): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2570): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2570): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2570): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2570): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2570): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2570): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2570): publish the event [tag = MOT_CHECKIN event name = LOG]
D/AndroidRuntime( 6081): 
D/AndroidRuntime( 6081): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6081): CheckJNI is OFF
D/AndroidRuntime( 6081): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6095 uid=10340 gids={50340, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6081): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6095): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6095): Time to load native libraries: 2 ms (timestamps 4960-4962)
I/LibraryLoader( 6095): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6095): Binding Chromium to main looper Looper (main, tid 1) {1f8049dd}
,I/LibraryLoader( 6095): Expected native library version number "",actual native library version number ""
,I/chromium( 6095): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6095): Initializing chromium process, singleProcess=true
W/art     ( 6095): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6095): ApplicationContext is null in ApplicationStatus
,W/chromium( 6095): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6095): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6095): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6095): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6095): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6095): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6095): Local Branch: 
I/Adreno-EGL( 6095): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6095): Local Patches: NONE
I/Adreno-EGL( 6095): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{25de102d u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e7838c8:true
,W/art     ( 6095): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6095): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6095): CordovaWebView is running on device made by: motorola
,W/art     ( 6095): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6095): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6095): Render dirty regions requested: true
,D/Atlas   ( 6095): Validating map...
,W/chromium( 6095): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  883): Explicit concurrent mark sweep GC freed 12668(688KB) AllocSpace objects, 2(210KB) LOS objects, 33% free, 20MB/30MB, paused 1.746ms total 122.236ms
,I/OpenGLRenderer( 6095): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6095): Enabling debug mode 0
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1161
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s85ms (total +1s161ms)
,W/IInputConnectionWrapper( 6095): showStatusIcon on inactive InputConnection
,I/ClearcutLoggerApiImpl( 1617): disconnect managed GoogleApiClient
,V/AlarmManager(  883): send {296b290d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {296b290d, *walarm*:com.google.android.intent.action.SEND_IDLE} [6ms]
,E/Adreno-ES20( 6095): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6095): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6095): Cannot call determinedVisibility() - never saw a connection for the pid: 6095
,D/JsMessageQueue( 6095): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6095): JniHelper::setJavaVM(0xb73dd310), pthread_self() = -1216955112
,D/JX-Cordova( 6095): jxcore cordova android initializing
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,W/jxcore-log( 6095): Initializing JXcore engine
W/jxcore-log( 6095): JXcore engine is ready
,W/jxcore-log( 6095): Starting JXcore engine
,W/.test.thalitest( 6095): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10340 path="socket:[6357]" dev="sockfs" ino=6357 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6095): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10340 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6095): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10340 path="socket:[7633]" dev="sockfs" ino=7633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6095): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10340 path="socket:[27173]" dev="sockfs" ino=27173 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6095): Platform android
W/jxcore-log( 6095): 
W/jxcore-log( 6095): Process ARCH arm
W/jxcore-log( 6095): 
,I/jxcore-log( 6095): JXcore Cordova bridge is ready!
I/jxcore-log( 6095): 
,W/jxcore-log( 6095): JXcore engine is started
,I/Choreographer( 6095): Skipped 171 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6095): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6095): Toggling radios to true
I/jxcore-log( 6095): 
,D/BluetoothAdapter( 6095): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=6095, uid=10340
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6095): Radios toggled
I/jxcore-log( 6095): 
,I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  295):  STA Disconnected !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  295): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
D/TCMD    (  476): NL - Read 68 bytes from update socket.
I/MDMCTBK (  295): set_property_value, Enter
D/TCMD    (  476): NL - message type is RTM_NEWLINK
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  883): InitialState.processMessage what=4
I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883):  0
D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/TCMD    (  476): NL - Read 60 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 21
D/TCMD    (  476): Listening for incoming client connection request
,V/NativeCrypto( 1617): Read error: ssl=0xb75fa9d8: I/O error during system call, Connection timed out,
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,V/NativeCrypto( 1617): SSL shutdown failed: ssl=0xb75fa9d8: I/O error during system call, Broken pipe
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/WifiMetrics(  883): connected time updated 130147
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6159 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=null
D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService(  883): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6159): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6187 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 5831:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_5831/cgroup.procs: No such file or directory
,W/ResourcesManager( 6187): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  295): Event received = WPS-AP-AVAILABLE-AUTH 
,I/wpa_supplicant( 1415): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  295): Event received = Trying to associate with
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1415): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  883): [1,449,063,233,247 ms] noteScanEnd no scan source
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1e8fcac5 sup_state=SCANNING debouncing=false
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6187): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6187): MmsConfig.loadMmsSettings
I/Babel_SMS( 6187): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6187): MmsConfig.loadFromDatabase
,D/TCMD    (  476): NL - Read 312 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 192 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,I/wpa_supplicant( 1415): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  295): Event received = Associated with c0:ff:d4
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1415): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  295): Event received = WPA: Key negotiation com
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/MDMCTBK (  295): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295):  STA Connected !!
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
E/MDMCTBK (  295): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
D/MDMCTBK (  295): get_freq !!, resp=2462
I/MDMCTBK (  295): get_freq !!, Strip data
I/MDMCTBK (  295): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1219809824
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  883): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d229919 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d229919 target=com.android.internal.util.StateMachine$SmHandler }
,E/Babel_SMS( 6187): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6187): MmsConfig.loadFromResources
,E/Babel_SMS( 6187): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6187): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6187): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6187): startup - clean
,I/Babel   ( 6187): deleted: false for 0
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6187): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6187): Unsupported mime video/mpeg2
,E/DHCPCD  ( 6226): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6226): version 5.5.6 starting
,E/DHCPCD  ( 6226): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6226): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6226): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/VideoCapabilities( 6187): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 5731:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/DHCPCD  ( 6226): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6226): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 6226): wlan0: sending REQUEST (xid 0xf31e67b8), next in 3.70 seconds
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_5731/cgroup.procs: No such file or directory
,I/vclib   ( 6187): onServiceConnected
,W/Babel   ( 6187): Attempted to change video mute state without an active call.
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/DHCPCD  ( 6226): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 6226): wlan0: leased 192.168.1.134 for 86400 seconds
D/DHCPCD  ( 6226): wlan0: adding IP address 192.168.1.134/24
D/DHCPCD  ( 6226): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6226): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6226): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  476): NL - Read 60 bytes from update socket.
,D/TCMD    (  476): NL - ignore NL message, type = 20
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/DHCPCD  ( 6226): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.134
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  883): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  883): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524290
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 13:33:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449063235505], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449063235479]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1294): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1537): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1537): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1470): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2570): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6289 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1470): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2570): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/Central_PollingManager( 1470): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2570): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2570): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2570): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2570): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2570): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2570): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2570): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2570): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2570): [debug] > CusSM.onRadioDown
,I/MusicStore( 6289): Database version: 120
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6095): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): my name is : motorola-XT1072_PT1657
I/jxcore-log( 6095): 
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6289): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/jxcore-log( 6095): attempting to connect to test coordinator
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): check test folder
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): found test : ./testFindPeers.js
I/jxcore-log( 6095): 
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6289): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6289): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/jxcore-log( 6095): found test : ./testReConnect.js
I/jxcore-log( 6095): 
,W/ResourcesManager( 6289): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6289): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 6095): found test : ./testSendData.js
I/jxcore-log( 6095): 
,V/JNIHelp ( 6289): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/jxcore-log( 6095): Test app app.js loaded
I/jxcore-log( 6095): 
,I/Choreographer( 6095): Skipped 227 frames!  The application may be doing too much work on its main thread.
I/chromium( 6095): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ActivityThread( 6289): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6289): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a139609: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6289): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6289): GMSCore installation verified
,I/ConfigStore( 6289): Config Database version: 1
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MediaRouter( 6289): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6289): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6289): type=WIFI subType= reason=null isConnected=true
,V/AlarmManager(  883): send {3fc3d07, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/NetworkMonitor( 6289): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6332 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6289): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6289): Using platform SSLCertificateSocketFactory
,V/Mms     ( 6332): mnc/mcc: 
V/Mms     ( 6332): tag: int value: recipientLimit - 20
V/Mms     ( 6332): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6332): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6332): tag: int value: maxSubjectLength - 80
V/Mms     ( 6332): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6332): tag: bool value: enableGroupMms - false
,V/Mms     ( 6332):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 75548(4MB) AllocSpace objects, 19(327KB) LOS objects, 40% free, 12MB/21MB, paused 1.195ms total 95.360ms
,I/ActivityManager(  883): Killing 5960:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,E/DataBuffer( 1617): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@250dcf9)
,E/DataBuffer( 1617): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@158243e)
,E/DataBuffer( 1617): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3386829f)
,E/DataBuffer( 1617): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@120c3fec)
E/DataBuffer( 1617): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7394fb5)
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_5960/cgroup.procs: No such file or directory
,W/ResourcesManager( 6332): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6364 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 5911:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 6364): Register our PhoneStateListener
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_5911/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6364): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6364): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 5858:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_5858/cgroup.procs: No such file or directory
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449063146072 min interval config: 0 actual interval: 90735
,I/CheckinService( 1966): Checking schedule, now: 1449063236821 next: 1449063176039
I/CheckinService( 1966): active receiver: enabled
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1966): Preparing to send checkin request
I/EventLogService( 1966): Accumulating logs since 1449063143106
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6389 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 45106(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.519ms total 126.020ms
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6406 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 322us total 24.685ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.794ms
,W/ResourcesManager( 6406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.257ms
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6427 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MultiDex( 6406): VM with version 2.1.0 has multidex support
I/MultiDex( 6406): install
I/MultiDex( 6406): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6406): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/Babel   ( 6187): connection state changed from UNKNOWN to CONNECTED
,W/ActivityThread( 6406): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6406): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@233b4ed6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6406): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6406): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 6406): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/WVCdm   (  298): Instantiating CDM.
I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/NativeLibraryUtils( 6406): Install completed successfully. count=13 extracted=0
D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb5036960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb8bab7a0, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bd1e18, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ca5f90, idLength=0xb55dc730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=2594763927
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8bac220
D/DrmWidevineDash(  298): message_length=1591, signature=0xb8bda118, signature_length=3042821908
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6427): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6427):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6427):   adb logcat -s GAv4
,W/GAv4    ( 6427): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6427): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6427): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 6427): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6427): Time to load native libraries: 2 ms (timestamps 4948-4950)
I/LibraryLoader( 6427): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6427): Binding Chromium to main looper Looper (main, tid 1) {18231986}
,I/LibraryLoader( 6427): Expected native library version number "",actual native library version number ""
I/chromium( 6427): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/BrowserStartupController( 6427): Initializing chromium process, singleProcess=true
,W/art     ( 6427): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6427): ApplicationContext is null in ApplicationStatus
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,W/chromium( 6427): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6427): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6427): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6427): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6427): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6427): Local Branch: 
I/Adreno-EGL( 6427): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6427): Local Patches: NONE
I/Adreno-EGL( 6427): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb54dc960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb8b75290, dataLength=8
,D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bac220, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ca5fd0, idLength=0xb55dc730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=594510913
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8bac220
D/DrmWidevineDash(  298): message_length=1626, signature=0xb8c69080, signature_length=3042821908
,W/AudioManagerAndroid( 6427): Requires BLUETOOTH permission
,I/NSApplication( 6427): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6509 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6159:com.motorola.context/u0a8 (adj 15): empty #7
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6159/cgroup.procs: No such file or directory
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2570): now: 205291 ,futureTime: 9223372036854775807
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2570): now: 205293 ,futureTime: 9223372036854775807
,D/PollingManager( 2570): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2570): now: 205294 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2570): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1470): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2570): [debug] > PollingManagerService, now: 205304 ,futureTime: 76810178
,I/NetworkMonitor( 6289): type=WIFI subType= reason=null isConnected=true
D/Central_PollingManager( 1470): now: 205310 ,futureTime: 86473780
D/Central_PollingManager( 1470): Polling alarm set to expire at: 86473780 Current Time: 205310
,D/OtaApp  ( 2570): [debug] > Polling alarm set to expire at: 76810178 Current Time: 205305
,D/OtaApp  ( 2570): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2570): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2570): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2570): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2570): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2570): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2570): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2570): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2570): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2570): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2570): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2570): createDeviceIdOrLogin update_device
,D/Checkin ( 2570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2570): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2570): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2570): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2570): createDeviceIdOrLogin update_device
D/Checkin ( 2570): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 6529): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/MMApiProvisionService( 2570): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2570): set mOutstandingReq to true.
,I/ Nonce  ( 2570):  Nonce getNonce 
I/ Nonce  ( 2570):  Nonce Request 
I/ Nonce  ( 2570):  Nonce execute Request 
,D/MMApiWebService( 2570): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 5020(232KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 811us total 40.096ms
,I/art     ( 2570): Explicit concurrent mark sweep GC freed 14403(806KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 1.053ms total 104.825ms
,D/MMApiProvisionService( 2570): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2570): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2570): createDeviceIdOrLogin update_device
,D/Checkin ( 2570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2570): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2570): generating token using payload instead of using session token
,D/ Nonce  ( 2570):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2570): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2570): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 6529): dex2oat took 253.905ms (threads: 4)
,I/Adreno-EGL( 6406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6406): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6406): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6406): Local Branch: 
I/Adreno-EGL( 6406): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6406): Local Patches: NONE
I/Adreno-EGL( 6406): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6541 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6289:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524295
,I/Adreno-EGL( 6406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6406): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6406): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6406): Local Branch: 
I/Adreno-EGL( 6406): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6406): Local Patches: NONE
I/Adreno-EGL( 6406): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6289/cgroup.procs: No such file or directory
,W/ResourcesManager( 6541): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/Adreno-EGL( 6406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6406): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6406): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6406): Local Branch: 
I/Adreno-EGL( 6406): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6406): Local Patches: NONE
I/Adreno-EGL( 6406): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6406): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6406): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6406): Local Branch: 
I/Adreno-EGL( 6406): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6406): Local Patches: NONE
I/Adreno-EGL( 6406): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6562 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6585 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6364:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 6562): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 6332:com.android.mms/u0a23 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6364/cgroup.procs: No such file or directory
,I/ Nonce  ( 2570):  Nonce Reponse 
,D/        ( 2570): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"6e332109-5e45-41d4-b892-f92331d3884d"}
,D/MMApiWSBase( 2570): doRequest(): /v1/gdi/nonce.json resp length: 61
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6332/cgroup.procs: No such file or directory
,I/ Nonce  ( 2570):  Nonce Handle Reponse 
D/MMApiProvisionService( 2570): mOutstandingReq set to false
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/CheckinTask( 1966): Sending checkin request (9433 bytes)
,I/art     (  883): Explicit concurrent mark sweep GC freed 13953(685KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.658ms total 112.286ms
,D/MMApiProvisionService( 2570):  pTime 1449056434640 sExp 172742 cTime 1449063239831 tTime 1449229176640
D/MMApiProvisionService( 2570):  No login Required 
,I/MusicStore( 6585): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6585): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6585): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6585): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6585): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6585): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a139609: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6585): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6585): GMSCore installation verified
,I/ConfigStore( 6585): Config Database version: 1
,W/DataUsage( 2570): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2570): publish the event [tag = MOT_CCE event name = LOG]
,I/MediaRouter( 6585): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6585): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6585): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6585): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6630 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6585): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6585): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 6389:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/Mms     ( 6630): mnc/mcc: 
,V/Mms     ( 6630): tag: int value: recipientLimit - 20
,V/Mms     ( 6630): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6630): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6630): tag: int value: maxSubjectLength - 80
V/Mms     ( 6630): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6630): tag: bool value: enableGroupMms - false
V/Mms     ( 6630):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6389/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,W/ResourcesManager( 6630): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6665 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6187:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6187/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6665): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6665): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6665): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 6427:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_6427/cgroup.procs: No such file or directory
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449063146072 min interval config: 0 actual interval: 94627
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6691 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1449063240823 next: 1449664377813
,I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checking schedule, now: 1449063240841 next: 1449664377813
I/CheckinService( 1966): active receiver: disabled
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1449063240844
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6709 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6509:com.android.chrome/u0a52 (adj 15): empty #7
,I/jxcore-log( 6095): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6095): 
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_6509/cgroup.procs: No such file or directory
,W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Killing 6562:android.process.acore/u0a7 (adj 13): empty #7
,I/Babel_SMS( 6709): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6709): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6709): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6709): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6709): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6709): MmsConfig.loadFromResources
E/Babel_SMS( 6709): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6709): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  883): Killing 6541:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6562/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6541/cgroup.procs: No such file or directory
,W/Settings( 6709): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6709): startup - clean
,I/Babel   ( 6709): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6744 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6709): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6709): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6709): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6744): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 6744): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6744):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6744):   adb logcat -s GAv4
,W/ContextImpl( 6744): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6744): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6744): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/vclib   ( 6709): onServiceConnected
,W/Babel   ( 6709): Attempted to change video mute state without an active call.
W/GAv4    ( 6744): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6744): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,W/GAv4    ( 6744): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6709): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 6585:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6585/cgroup.procs: No such file or directory
,I/WebViewFactory( 6744): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6744): Time to load native libraries: 2 ms (timestamps 8989-8991)
I/LibraryLoader( 6744): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6744): Binding Chromium to main looper Looper (main, tid 1) {18231986}
,I/LibraryLoader( 6744): Expected native library version number "",actual native library version number ""
I/chromium( 6744): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6744): Initializing chromium process, singleProcess=true
,W/art     ( 6744): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6744): ApplicationContext is null in ApplicationStatus
,W/chromium( 6744): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6744): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6744): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6744): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6744): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6744): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6744): Local Branch: 
I/Adreno-EGL( 6744): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6744): Local Patches: NONE
I/Adreno-EGL( 6744): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6744): Starting up...
,W/AudioManagerAndroid( 6744): Requires BLUETOOTH permission
,I/art     (  883): Explicit concurrent mark sweep GC freed 11555(563KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.636ms total 119.709ms
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6820 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6630:com.android.mms/u0a23 (adj 15): empty #7
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 30420(1456KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/19MB, paused 1.128ms total 57.171ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.391ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.750ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.598ms
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6630/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6844 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6665:com.google.android.setupwizard/u0a35 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6665/cgroup.procs: No such file or directory
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6867 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  883): Killing 6709:com.google.android.talk/u0a70 (adj 13): empty #7
,I/ContactLocale( 6867): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 6691:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6709/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6691/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2570): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2570): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2570): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2570): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2570): onServiceConnected()
,D/GetNotificationsWS( 2570): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2570): unbindWebServices(): un-registering our AIDL callback...
,V/AlarmManager(  883): done {3fc3d07, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6765ms]
,I/PushService( 2570): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6904 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableService( 1772): callingUid 10016, callindPid: 1772
,E/MDM     ( 1772): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1617): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1617): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1966): Restart initialization of location
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6936 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1772): No location to return for getLastLocation()
,W/FusedLocationProvider( 1617): location=null
,I/MusicStore( 6936): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6936): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6936): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6936): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6936): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6936): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6936): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6936): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6936): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a139609: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6936): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6936): GMSCore installation verified
,I/ConfigStore( 6936): Config Database version: 1
,I/MediaRouter( 6936): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6936): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6936): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6936): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6982 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6936): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6936): Using platform SSLCertificateSocketFactory
,V/Mms     ( 6982): mnc/mcc: 
V/Mms     ( 6982): tag: int value: recipientLimit - 20
V/Mms     ( 6982): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6982): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6982): tag: int value: maxSubjectLength - 80
V/Mms     ( 6982): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6982): tag: bool value: enableGroupMms - false
,V/Mms     ( 6982):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7013 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6744:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_6744/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7013): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7013): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7013): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 6820:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_6820/cgroup.procs: No such file or directory
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449063240844 min interval config: 0 actual interval: 3741
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1966): Checking schedule, now: 1449063244607 next: 1449063270813
I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449063240844 min interval config: 0 actual interval: 3771
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7038 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6844:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/CheckinService( 1966): Checking schedule, now: 1449063244689 next: 1449063270813
,I/CheckinService( 1966): active receiver: disabled
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6844/cgroup.procs: No such file or directory
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7038): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7038): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7038): MmsConfig.loadMmsSettings
I/Babel_SMS( 7038): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7038): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7038): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7038): MmsConfig.loadFromResources
,E/Babel_SMS( 7038): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7038): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7038): startup - clean
,I/Babel   ( 7038): deleted: false for 0
,I/art     (  883): Explicit concurrent mark sweep GC freed 11013(500KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.624ms total 113.171ms
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7069 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7038): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7038): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7038): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7038): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7038): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7038): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7038): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7038): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7038): onServiceConnected
,W/Babel   ( 7038): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7069): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7069): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7069): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7069):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7069):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7069): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
I/Babel   ( 7038): connection state changed from UNKNOWN to CONNECTED
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7069): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  883): Killing 6867:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6867/cgroup.procs: No such file or directory
,W/GAv4    ( 7069): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7069): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7069): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ProcessCpuTracker(  883): Skipping unknown process pid 7094
W/ProcessCpuTracker(  883): Skipping unknown process pid 7097
,I/WebViewFactory( 7069): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7069): Time to load native libraries: 1 ms (timestamps 2586-2587)
I/LibraryLoader( 7069): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7069): Binding Chromium to main looper Looper (main, tid 1) {18231986}
,I/LibraryLoader( 7069): Expected native library version number "",actual native library version number ""
I/chromium( 7069): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7069): Initializing chromium process, singleProcess=true
,W/art     ( 7069): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7069): ApplicationContext is null in ApplicationStatus
,W/chromium( 7069): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7069): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7069): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7069): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7069): Local Branch: 
I/Adreno-EGL( 7069): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7069): Local Patches: NONE
I/Adreno-EGL( 7069): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7069): Starting up...
,W/AudioManagerAndroid( 7069): Requires BLUETOOTH permission
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7141 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6936:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6936/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7160 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6982:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6982/cgroup.procs: No such file or directory
,W/ResourcesManager( 7160): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7180 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.951ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.196ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 21.656ms
,I/ActivityManager(  883): Killing 6904:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7180): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7013:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6904/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2570): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7013/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2570): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2570): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2570): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2570): onServiceConnected()
D/GetNotificationsWS( 2570): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2570): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2570): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2570): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2570): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2570): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2570): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2570): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2570): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7215 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2570): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2570): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2570): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2570): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2570): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2570): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2570): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1413): onFinishInput()
W/IInputConnectionWrapper( 6095): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7215): Register our PhoneStateListener
,V/SetupWizard( 7215): Connected to Gservices successfully
,I/ActivityManager(  883): Killing 6406:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,185
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6406/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7236 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,D/GCM     ( 1617): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@8fc7fa5
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsNetworkLocationProvi( 1772): DISABLE
,I/GCoreNlp( 1772): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/ActivityManager(  883): Killing 7069:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7069/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1617): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1617): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7270 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 19015(929KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.370ms total 115.144ms
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7295 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7314 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7141:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7141/cgroup.procs: No such file or directory
,W/asset   ( 7314): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7314): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7314): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7314): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7038): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7038): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7038): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 7038): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7038): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7343 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7160:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7160/cgroup.procs: No such file or directory
,D/Finsky  ( 7343): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7343): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7343): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7343): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7343): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7343): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7343): Skipping gmscore version check
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1fed0f7f new=com.google.android.velvet.VelvetApplication@1fed0f7f
,I/UpdateIcingCorporaServi( 7270): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7401 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7343): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7343): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7270): UpdateCorporaTask done [took 147 ms] updated apps [took 147 ms] 
,I/ActivityManager(  883): Killing 7236:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7236/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7215:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7215/cgroup.procs: No such file or directory
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ActivityManager(  883): Killing 7295:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7295/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7038:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7038/cgroup.procs: No such file or directory
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311915, SEQNUM=4487, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-353, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312647, SEQNUM=4488, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-403, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312353, SEQNUM=4490, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-404, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ClearcutLoggerApiImpl( 1772): disconnect managed GoogleApiClient
,V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {24845119, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  883): send {391372bc, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  883): done {24845119, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [80ms]
,V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [94ms]
,V/AlarmManager(  883): done {391372bc, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [98ms]
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449063240844 min interval config: 0 actual interval: 45601
,I/CheckinService( 1966): Checking schedule, now: 1449063286457 next: 1449063270813
I/CheckinService( 1966): active receiver: enabled
,I/CheckinService( 1966): Preparing to send checkin request
I/EventLogService( 1966): Accumulating logs since 1449063236849
,I/CheckinRequestBuilder( 1966): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7464 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7464): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7464): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7464): VM with version 2.1.0 has multidex support
I/MultiDex( 7464): install
I/MultiDex( 7464): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 13636(829KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/19MB, paused 1.096ms total 63.186ms
,V/JNIHelp ( 7464): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7464): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7464): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@233b4ed6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7464): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1772): callingUid 10016, callindPid: 1772
,E/MDM     ( 1772): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1617): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1617): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1966): Restart initialization of location
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 7464): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 7464): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,W/GCoreFlp( 1772): No location to return for getLastLocation()
W/FusedLocationProvider( 1617): location=null
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,D/NativeLibraryUtils( 7464): Install completed successfully. count=13 extracted=0
,D/WVCdm   (  298): Instantiating CDM.
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
,E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xbee2a4e0
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb8c691b0, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bd1e18, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ca5fb0, idLength=0xb4e38730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=1151332128
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8bac220
D/DrmWidevineDash(  298): message_length=1591, signature=0xb8c65e48, signature_length=3034810132
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  298): CdmEngine::CloseSession
,D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f01000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb5036960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb8c691b0, dataLength=8
,D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bd1e18, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ca5fd0, idLength=0xb55dc730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=2329482230
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8bac220
D/DrmWidevineDash(  298): message_length=1626, signature=0xb8c5e838, signature_length=3042821908
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7509): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7509): dex2oat took 65.232ms (threads: 4)
,I/Adreno-EGL( 7464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7464): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7464): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7464): Local Branch: 
I/Adreno-EGL( 7464): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7464): Local Patches: NONE
I/Adreno-EGL( 7464): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7464): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7464): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7464): Local Branch: 
I/Adreno-EGL( 7464): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7464): Local Patches: NONE
I/Adreno-EGL( 7464): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7464): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7464): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7464): Local Branch: 
I/Adreno-EGL( 7464): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7464): Local Patches: NONE
I/Adreno-EGL( 7464): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7464): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7464): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7464): Local Branch: 
I/Adreno-EGL( 7464): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7464): Local Patches: NONE
I/Adreno-EGL( 7464): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Sending checkin request (9436 bytes)
,I/CheckinRequestBuilder( 1966): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1449063289289 next: 1449664426281
I/CheckinService( 1966): active receiver: disabled
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1449063289306
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7528 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 14621(781KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.542ms total 115.693ms
,D/PhoneMonitor( 7528): Register our PhoneStateListener
,V/SetupWizard( 7528): Connected to Gservices successfully
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1617): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  883): Killing 7270:com.google.android.googlequicksearchbox:search/u0a39 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7314:com.motorola.MotGallery2/u0a27 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7270/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7314/cgroup.procs: No such file or directory
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7553 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3dccce5
,V/GmsNetworkLocationProvi( 1772): DISABLE
,I/GCoreNlp( 1772): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/art     ( 1772): Explicit concurrent mark sweep GC freed 24174(1389KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 11MB/18MB, paused 971us total 64.045ms
,E/DataBuffer( 1772): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@6f1bce1)
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7593 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.959ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 19.661ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.695ms
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7610 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7343:com.android.vending/u0a32 (adj 15): empty #7
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7343/cgroup.procs: No such file or directory
,W/ResourcesManager( 7610): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7610): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7610): MmsConfig.loadMmsSettings
I/Babel_SMS( 7610): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7610): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7610): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7610): MmsConfig.loadFromResources
,E/Babel_SMS( 7610): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7610): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7610): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7610): startup - clean
,I/Babel   ( 7610): deleted: false for 0
,W/VideoCapabilities( 7610): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7647 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7610): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7610): Unsupported mime video/mpeg2
,W/asset   ( 7647): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7647): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7647): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7647): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7610): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7610): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7610): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7610): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7610): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7670 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7401:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7401/cgroup.procs: No such file or directory
,I/vclib   ( 7610): onServiceConnected
W/Babel   ( 7610): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7610): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7610): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7610): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/Finsky  ( 7670): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/System  ( 7610): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7610): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 7670): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7670): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7670): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7670): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7670): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7670): Skipping gmscore version check
,D/Finsky  ( 7670): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7670): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1fed0f7f new=com.google.android.velvet.VelvetApplication@1fed0f7f
I/UpdateIcingCorporaServi( 7553): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7725 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7725): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7553): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
,I/ActivityManager(  883): Killing 7528:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7528/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7464:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_7464/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  883): Killing 7593:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7593/cgroup.procs: No such file or directory
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ActivityManager(  883): Killing 7647:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7647/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1617): onCreate
,I/art     ( 1617): WaitForGcToComplete blocked for 5.012ms for cause DisableMovingGc
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1617): onDestroy
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311946, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=-571, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 5
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312197, SEQNUM=4515, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-632, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [35ms]
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312141, SEQNUM=4518, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-850, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312410, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1009, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {25127446, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7782 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [80ms]
,I/GAv4    ( 7782): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7782):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7782):   adb logcat -s GAv4
,W/GAv4    ( 7782): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7782): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7782): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  883): done {25127446, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [374ms]
,I/ActivityManager(  883): Killing 7610:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7610/cgroup.procs: No such file or directory
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312362, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-1884, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,V/AlarmManager(  883): send {36c5468e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {1c6d0607, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  883): send {2abe334, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT}
,V/AlarmManager(  883): done {36c5468e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,V/AlarmManager(  883): done {1c6d0607, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [43ms]
,V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [57ms]
,V/AlarmManager(  883): done {2abe334, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT} [176ms]
,I/art     (  883): Explicit concurrent mark sweep GC freed 21351(1156KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.599ms total 127.698ms
,I/EventLogService( 1966): Aggregate from 1449063286490 (log), 1449062035106 (data)
,D/UdcCache:FPQuery( 1966): Bootstrapping UDC settings cache for all accounts
,I/GoogleURLConnFactory( 1617): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1617): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/PhenotypeConfigurator( 1617): Server returned 404
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312943, SEQNUM=4530, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1935, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312047, SEQNUM=4531, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-95, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {d527eaf, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {d527eaf, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {35e098fc, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  883): done {35e098fc, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [21ms]
,V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311727, SEQNUM=4534, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-1176, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6095): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6095): 
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7858): 
D/AndroidRuntime( 7858): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7858): CheckJNI is OFF
D/AndroidRuntime( 7858): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10340 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 6095:com.test.thalitest/u0a340 (adj 9): stop com.test.thalitest
W/PackageSettings(  883): Skipping PackageSetting{158f42ca com.example.hello/10333} due to missing metadata
I/WindowState(  883): WIN DEATH: Window{10f63f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  883): Client connection lost with reason: 4
I/ActivityManager(  883):   Force finishing activity ActivityRecord{25de102d u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  883): Spurious death for ProcessRecord{107a6dda 6095:com.test.thalitest/u0a340}, curProc for 6095: null
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10340 user=0: pkg removed
I/ActivityManager(  883):   Force finishing activity ActivityRecord{25de102d u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  883): Duplicate finish request for ActivityRecord{25de102d u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 2967): Explicit concurrent mark sweep GC freed 11935(2MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 7MB/12MB, paused 931us total 46.393ms
I/ProcessStatsService(  883): Prepared write state in 12ms
I/ProcessStatsService(  883): Prepared write state in 25ms
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1772): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
I/art     ( 1573): Explicit concurrent mark sweep GC freed 5105(314KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 475us total 101.495ms
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
I/Decoder ( 1413): createOrResetDecoder
I/art     (  883): Explicit concurrent mark sweep GC freed 16609(1191KB) AllocSpace objects, 8(179KB) LOS objects, 33% free, 20MB/30MB, paused 3.370ms total 157.330ms
I/art     (  883): WaitForGcToComplete blocked for 82.254ms for cause Explicit
D/VoicemailCleanupService( 7180): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7890 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ConfigService( 1617): onCreate
W/asset   ( 7890): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7890): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7890): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7890): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
I/ProcessStatsService(  883): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-48-16.bin
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7910 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  883): Explicit concurrent mark sweep GC freed 6113(320KB) AllocSpace objects, 1(47KB) LOS objects, 33% free, 20MB/30MB, paused 2.679ms total 208.342ms
I/ActivityManager(  883): Killing 7670:com.android.vending/u0a32 (adj 15): empty #7
I/Launcher( 1573): Deferring update until onResume
D/AndroidRuntime( 7858): Shutting down VM
W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7670/cgroup.procs: No such file or directory
V/AlarmManager(  883): send {4cce25d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {36c5468e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  883): send {1cd0ed87, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  883): send {311e83bb, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  883): send {13c340d8, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  883): send {26f49c31, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  883): send {1ca39f16, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  883): send {2abe334, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT}
W/ContextImpl( 7910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7931 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7553:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7553/cgroup.procs: No such file or directory
V/AlarmManager(  883): done {4cce25d, *alarm*:android.intent.action.TIME_TICK} [215ms]
D/Finsky  ( 7931): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
E/RollingFileStream( 7931): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 7931): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7931): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7931): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 7931): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 7931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 7931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7931): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/SQLiteDatabase( 7931): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/SQLiteDatabase( 7931): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7931): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7931): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
