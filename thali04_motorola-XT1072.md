#### Test 5497026140aeaf4_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2613): no tags to log
D/Checkin ( 2613): publish the event [tag = MOT_CHECKIN event name = LOG]
I/art     ( 2613): Explicit concurrent mark sweep GC freed 29303(1776KB) AllocSpace objects, 6(119KB) LOS objects, 39% free, 11MB/19MB, paused 14.589ms total 97.354ms
D/BSUtils ( 2613): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2613): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2613): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2613): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1467): Explicit concurrent mark sweep GC freed 55804(3MB) AllocSpace objects, 37(1259KB) LOS objects, 39% free, 7MB/12MB, paused 774us total 44.523ms
D/BSUtils ( 2613): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/AndroidRuntime( 6508): 
D/AndroidRuntime( 6508): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6508): CheckJNI is OFF
I/BSUtils ( 2613): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2613): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6508): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     (  880): Explicit concurrent mark sweep GC freed 33495(2MB) AllocSpace objects, 2(221KB) LOS objects, 33% free, 20MB/30MB, paused 3.018ms total 127.502ms
D/BSUtils ( 2613): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2613): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6540 uid=10427 gids={50427, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6508): Shutting down VM
I/BSUtils ( 2613): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2613): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2613): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2613): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2613): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2613): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2613): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2613): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2613): publish the event [tag = MOT_CHECKIN event name = LOG]
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/AlarmManager(  880): send {21e8d077, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  880): done {21e8d077, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,I/WebViewFactory( 6540): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6540): Time to load native libraries: 6 ms (timestamps 6064-6070)
I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6540): Binding Chromium to main looper Looper (main, tid 1) {10df8279}
,I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
,I/chromium( 6540): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6540): Initializing chromium process, singleProcess=true
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6540): ApplicationContext is null in ApplicationStatus
,W/chromium( 6540): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6540): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6540): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6540): Local Branch: 
I/Adreno-EGL( 6540): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6540): Local Patches: NONE
I/Adreno-EGL( 6540): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
,D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@199a3c7c:true
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{27a37d38 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/AwContents( 6540): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6540): CordovaWebView is running on device made by: motorola
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6540): Render dirty regions requested: true
,D/Atlas   ( 6540): Validating map...
,W/chromium( 6540): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6540): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6540): Enabling debug mode 0
,I/Keyboard.Facilitator( 1418): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1035
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +881ms (total +1s35ms)
,W/IInputConnectionWrapper( 6540): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6540): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6540): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6540): Cannot call determinedVisibility() - never saw a connection for the pid: 6540
,D/JsMessageQueue( 6540): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6540): JniHelper::setJavaVM(0xb71d3310), pthread_self() = -1219084960
,D/JX-Cordova( 6540): jxcore cordova android initializing
,W/jxcore-log( 6540): Initializing JXcore engine
W/jxcore-log( 6540): JXcore engine is ready
,W/jxcore-log( 6540): Starting JXcore engine
,W/.test.thalitest( 6540): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10427 path="socket:[7358]" dev="sockfs" ino=7358 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6540): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10427 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6540): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10427 path="socket:[5654]" dev="sockfs" ino=5654 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6540): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10427 path="socket:[29741]" dev="sockfs" ino=29741 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6540): Platform android
W/jxcore-log( 6540): 
W/jxcore-log( 6540): Process ARCH arm
W/jxcore-log( 6540): 
,I/jxcore-log( 6540): JXcore Cordova bridge is ready!
I/jxcore-log( 6540): 
W/jxcore-log( 6540): JXcore engine is started
I/chromium( 6540): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6540): Toggling radios to true
I/jxcore-log( 6540): 
,D/BluetoothAdapter( 6540): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=6540, uid=10427
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6540): Radios toggled
I/jxcore-log( 6540): 
,I/wpa_supplicant( 1401): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1401): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  880): InitialState.processMessage what=4
E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1401): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1401): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 21
D/TCMD    (  453): Listening for incoming client connection request
,V/NativeCrypto( 1709): Read error: ssl=0xb74c4238: I/O error during system call, Connection timed out
V/NativeCrypto( 1709): SSL shutdown failed: ssl=0xb74c4238: I/O error during system call, Broken pipe
D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 129493
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6621 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1401): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1401): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1401): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  290): Clearing all IP addresses on wlan0
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,W/ResourcesManager( 6621): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6621): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6621): MmsConfig.loadMmsSettings
I/Babel_SMS( 6621): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6621): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6621): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6621): MmsConfig.loadFromResources
,E/Babel_SMS( 6621): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6621): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6621): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6621): startup - clean
,I/Babel   ( 6621): deleted: false for 0
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1401): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1401): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  880): [1,452,278,396,610 ms] noteScanEnd no scan source
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3e255f1d sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6656 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  453): NL - Read 312 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 192 bytes from update socket.
,D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
I/wpa_supplicant( 1401): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1401): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1401): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  453): NL - Read 1004 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
E/Tethering(  880): ApnList is empty for checkDunConfigured()
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
D/Tethering(  880):  upstream interface types: 
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
D/Tethering(  880):  0
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
D/Tethering(  880):  1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
D/Tethering(  880):  5
I/MDMCTBK (  292): set_property_value, Enter
D/Tethering(  880):  7
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
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213988480
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
W/ResourcesManager( 6656): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
E/wpa_supplicant( 1401): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1401): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bd0d6dc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bd0d6dc target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6621): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6621): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6621): Unsupported mime video/mpeg2
,I/ActivityManager(  880): Killing 6297:com.google.android.videos/u0a98 (adj 15): empty #7
,I/VideoCapabilities( 6621): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6621): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6621): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6621): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6621): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6678): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6678): version 5.5.6 starting
,E/DHCPCD  ( 6678): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6678): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6678): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/libprocessgroup(  880): failed to open /acct/uid_10098/pid_6297/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6404:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/vclib   ( 6621): onServiceConnected
,W/Babel   ( 6621): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6678): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6678): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6678): wlan0: sending REQUEST (xid 0x779c008d), next in 3.74 seconds
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6404/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6678): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6678): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6678): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6678): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6678): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6678): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 20
D/TCMD    (  453): Listening for incoming client connection request
,D/DHCPCD  ( 6678): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 18:39:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452278398861], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452278398842]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1531): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1467): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1467): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1467): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 6380): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6380): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6380): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2613): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2613): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2613): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2613): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2613): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2613): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2613): Registering with Alarm Manager to restart CCE
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6752 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.803ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 18.782ms
,D/CCE     ( 2613): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2613): Registering with Alarm Manager to restart CCE
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.021ms
,D/OtaApp  ( 2613): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2613): [debug] > CusSM.onRadioDown
,V/Mms     ( 6752): mnc/mcc: 
,V/Mms     ( 6752): tag: int value: recipientLimit - 20
V/Mms     ( 6752): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6752): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6752): tag: int value: maxSubjectLength - 80
V/Mms     ( 6752): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6752): tag: bool value: enableGroupMms - false
V/Mms     ( 6752):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6752): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6777 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6155:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6155/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6777): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6777): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6777): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=6798 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6007:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6007/cgroup.procs: No such file or directory
,W/ResourcesManager( 6798): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6798): VM with version 2.1.0 has multidex support
I/MultiDex( 6798): install
I/MultiDex( 6798): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6798): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6798): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6798): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37f8ef18: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6798): Installed default security provider GmsCore_OpenSSL
,I/CheckinService( 6798): Checkin interval check for package: unspecified last checkin: 1452278311222 min interval config: 0 actual interval: 89417
,D/NativeLibraryUtils( 6798): Install completed successfully. count=14 extracted=0
,I/CheckinService( 6798): Disabling old GoogleServicesFramework version
,I/CheckinService( 6798): Checking schedule, now: 1452278400689 next: 1452278341182
I/CheckinService( 6798): active receiver: enabled
,I/CheckinService( 6798): Preparing to send checkin request
,I/EventLogService( 6798): Accumulating logs since 1452278308138
,I/iu.SyncManager( 6798): SYNC; picasa accounts
,D/NetworkLogImpl( 6798): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6798): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6798): num queued entries: 0
,I/iu.UploadsManager( 6798): num updated entries: 0
,I/iu.SyncManager( 6798): NEXT; no task
,I/art     ( 6798): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6798): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6846 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6798): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6798): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  880): Explicit concurrent mark sweep GC freed 48874(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.721ms total 127.595ms
,V/AlarmManager(  880): send {1d9c3d04, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3a01a7af, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  880): done {1d9c3d04, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6876 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6621): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6656:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6656/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6896 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1467): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1467): now: 206344 ,futureTime: 86475081
D/Central_PollingManager( 1467): Polling alarm set to expire at: 86475081 Current Time: 206344
,D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2613): now: 206347 ,futureTime: 9223372036854775807
D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2613): now: 206348 ,futureTime: 9223372036854775807
D/PollingManager( 2613): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2613): now: 206348 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2613): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2613): [debug] > PollingManagerService, now: 206353 ,futureTime: 77765427
,D/OtaApp  ( 2613): [debug] > Polling alarm set to expire at: 77765427 Current Time: 206354
,I/NetworkMonitor( 6380): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2613): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2613): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2613): createDeviceIdOrLogin update_device
,D/Checkin ( 2613): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2613): Not proxy app, so login/provision not allowed
,W/ResourcesManager( 6896): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6896): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1467): Explicit concurrent mark sweep GC freed 5125(236KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.858ms total 31.902ms
,D/MMApiProvisionService( 2613): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2613): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2613): createDeviceIdOrLogin update_device
,D/Checkin ( 2613): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2613): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2613): set mOutstandingReq to true.
I/ Nonce  ( 2613):  Nonce getNonce 
I/ Nonce  ( 2613):  Nonce Request 
I/ Nonce  ( 2613):  Nonce execute Request 
,I/MultiDex( 6896): VM with version 2.1.0 has multidex support
I/MultiDex( 6896): install
I/MultiDex( 6896): VM has multidex support, MultiDex support library is disabled.
,D/MMApiWebService( 2613): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2613): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2613): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2613): createDeviceIdOrLogin update_device
,D/Checkin ( 2613): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2613): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2613): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2613): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2613): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
V/JNIHelp ( 6896): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/OtaApp  ( 2613): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2613): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2613): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2613): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2613): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2613): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/OtaApp  ( 2613): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
D/MMApiWebService( 2613): generating token using payload instead of using session token
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/ActivityThread( 6896): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6896): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6896): Installed default security provider GmsCore_OpenSSL
I/GAv4    ( 6876): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6876):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6876):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,D/ Nonce  ( 2613):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,W/ContextImpl( 6876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/MMApiWSBase( 2613): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2613): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6876): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 6896): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6896): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GAv4    ( 6876): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6876): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 6896): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
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
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb558a960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb79fb628, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79091c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a06d58, idLength=0xb13a0730
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
D/WVCdm   (  296): PrepareKeyRequest: nonce=801317051
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb792cf40
D/DrmWidevineDash(  296): message_length=1591, signature=0xb793ddd8, signature_length=2973370132
,I/WebViewFactory( 6876): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6876): Time to load native libraries: 2 ms (timestamps 7120-7122)
I/LibraryLoader( 6876): Expected native library version number "",actual native library version number ""
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,V/WebViewChromiumFactoryProvider( 6876): Binding Chromium to main looper Looper (main, tid 1) {206bb932}
,I/LibraryLoader( 6876): Expected native library version number "",actual native library version number ""
,I/chromium( 6876): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6876): Initializing chromium process, singleProcess=true
W/art     ( 6876): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6876): ApplicationContext is null in ApplicationStatus
,W/chromium( 6876): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6876): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6876): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6876): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6876): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6876): Local Branch: 
I/Adreno-EGL( 6876): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6876): Local Patches: NONE
I/Adreno-EGL( 6876): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6876): Starting up...
W/AudioManagerAndroid( 6876): Requires BLUETOOTH permission
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6970 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6380:com.google.android.music:main/u0a80 (adj 15): empty #7
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
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
,D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb12a0960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb79fbaa8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79091c8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a06d98, idLength=0xb13a0730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
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
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2799539732
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb79091c8
D/DrmWidevineDash(  296): message_length=1626, signature=0xb793ddd8, signature_length=2973370132
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6380/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/ Nonce  ( 2613):  Nonce Reponse 
D/        ( 2613): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"39b65f4e-87f9-47fa-ab8b-601685b714c6"}
D/MMApiWSBase( 2613): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2613):  Nonce Handle Reponse 
D/MMApiProvisionService( 2613): mOutstandingReq set to false
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6993 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6752:com.android.mms/u0a23 (adj 15): empty #7
,I/art     ( 2613): Explicit concurrent mark sweep GC freed 17845(1039KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/19MB, paused 1.322ms total 68.159ms
,D/MMApiProvisionService( 2613):  pTime 1452107623780 sExp 172742 cTime 1452278403381 tTime 1452280365780
,D/MMApiProvisionService( 2613):  No login Required 
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6752/cgroup.procs: No such file or directory
,W/ResourcesManager( 6993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7014 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/DataUsage( 2613): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2613): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7039 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6846:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7014): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 6777:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6846/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6777/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 12458(604KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.047ms total 124.004ms
,I/dex2oat ( 7059): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/MusicStore( 7039): Database version: 120
,I/dex2oat ( 7059): dex2oat took 98.954ms (threads: 4)
,I/Adreno-EGL( 6896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6896): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6896): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6896): Local Branch: 
I/Adreno-EGL( 6896): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6896): Local Patches: NONE
I/Adreno-EGL( 6896): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7039): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7039): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7039): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6896): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6896): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6896): Local Branch: 
I/Adreno-EGL( 6896): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6896): Local Patches: NONE
I/Adreno-EGL( 6896): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/JNIHelp ( 7039): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Adreno-EGL( 6896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6896): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6896): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6896): Local Branch: 
I/Adreno-EGL( 6896): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6896): Local Patches: NONE
I/Adreno-EGL( 6896): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityThread( 7039): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7039): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@237ac765: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7039): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7039): GMSCore installation verified
,I/ConfigStore( 7039): Config Database version: 1
,I/Adreno-EGL( 6896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6896): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6896): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6896): Local Branch: 
I/Adreno-EGL( 6896): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6896): Local Patches: NONE
I/Adreno-EGL( 6896): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/MediaRouter( 7039): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7039): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/CheckinRequestBuilder( 6798): Classify the device as Phone.
,I/NetworkMonitor( 7039): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7039): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7083 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7039): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7039): Using platform SSLCertificateSocketFactory
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
,I/CheckinTask( 6798): Sending checkin request (9599 bytes)
I/ActivityManager(  880): Killing 6621:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6621/cgroup.procs: No such file or directory
,V/Mms     ( 7083): mnc/mcc: 
V/Mms     ( 7083): tag: int value: recipientLimit - 20
V/Mms     ( 7083): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7083): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7083): tag: int value: maxSubjectLength - 80
V/Mms     ( 7083): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7083): tag: bool value: enableGroupMms - false
V/Mms     ( 7083):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7083): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7112 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.356ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.455ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 21.184ms
,I/ActivityManager(  880): Killing 6876:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7112): Register our PhoneStateListener
,I/CheckinRequestBuilder( 6798): Checkin reason type: 8 attempt count: 1
,E/libprocessgroup(  880): failed to kill 1 processes for processgroup 6876
,E/ActivityThread( 6798): Failed to find provider info for com.google.android.wearable.settings
,D/MobileConnectivityChangeReceiver( 7112): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7112): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6798): Checkin interval check for package: unspecified last checkin: 1452278311222 min interval config: 0 actual interval: 94720
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7140 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6970:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_6970/cgroup.procs: No such file or directory
,I/art     ( 6129): Explicit concurrent mark sweep GC freed 1492(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 393us total 37.665ms
,I/CheckinRequestBuilder( 6798): Classify the device as Phone.
,I/CheckinTask( 6798): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6798): Checking schedule, now: 1452278406446 next: 1452879543440
I/CheckinService( 6798): active receiver: disabled
,I/CheckinService( 6798): Checking schedule, now: 1452278406470 next: 1452879543440
I/CheckinService( 6798): active receiver: disabled
,D/CheckinService( 6798): Recording last checkin time for package unspecified as 1452278406473
,I/ActivityManager(  880): Killing 6993:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7014:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6993/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7014/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7176 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7039:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7039/cgroup.procs: No such file or directory
,W/ResourcesManager( 7176): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7176): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7176): MmsConfig.loadMmsSettings
I/Babel_SMS( 7176): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7176): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7176): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7176): MmsConfig.loadFromResources
,E/Babel_SMS( 7176): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7176): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7176): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7176): startup - clean
,I/Babel   ( 7176): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7212 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7176): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7176): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7176): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7176): onServiceConnected
W/Babel   ( 7176): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7212): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7212):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7212):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7212): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7176): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 7212): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  880): Killing 7083:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7212): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7083/cgroup.procs: No such file or directory
,I/WebViewFactory( 7212): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7212): Time to load native libraries: 1 ms (timestamps 2714-2715)
I/LibraryLoader( 7212): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7212): Binding Chromium to main looper Looper (main, tid 1) {206bb932}
,I/LibraryLoader( 7212): Expected native library version number "",actual native library version number ""
,I/chromium( 7212): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7212): Initializing chromium process, singleProcess=true
,W/art     ( 7212): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7212): ApplicationContext is null in ApplicationStatus
,W/chromium( 7212): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7212): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7212): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7212): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7212): Local Branch: 
I/Adreno-EGL( 7212): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7212): Local Patches: NONE
I/Adreno-EGL( 7212): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7212): Requires BLUETOOTH permission
,I/NSApplication( 7212): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7276 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7112:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7112/cgroup.procs: No such file or directory
,I/jxcore-log( 6540): Test app app.js loaded
I/jxcore-log( 6540): 
,I/chromium( 6540): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7295 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7140:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7140/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 11562(585KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.529ms total 121.345ms
,W/ResourcesManager( 7295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7318 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7212:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7318): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7176:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2613): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7212/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7176/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2613): bindWebServices(): registering our AIDL callback...
I/SundryService( 2613): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2613): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2613): onServiceConnected()
,D/GetNotificationsWS( 2613): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2613): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2613): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/MDM     ( 1709): [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6798): Restart initialization of location
,D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/GCoreFlp( 1709): No location to return for getLastLocation()
,W/FusedLocationProvider( 1709): location=null
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7358 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/IcingInternalCorpora( 6798): getNumBytesRead when not calculated.
,V/AlarmManager(  880): done {3a01a7af, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8418ms]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7386 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7386): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7386): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7386): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7386): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7386): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7386): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@237ac765: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7386): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7386): GMSCore installation verified
,I/ConfigStore( 7386): Config Database version: 1
,I/MediaRouter( 7386): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7386): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7386): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7386): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7422 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7386): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7386): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7276:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7276/cgroup.procs: No such file or directory
,V/Mms     ( 7422): mnc/mcc: 
V/Mms     ( 7422): tag: int value: recipientLimit - 20
V/Mms     ( 7422): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7422): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7422): tag: int value: maxSubjectLength - 80
V/Mms     ( 7422): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7422): tag: bool value: enableGroupMms - false
V/Mms     ( 7422):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7422): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7448 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7295:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7448): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7295/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7448): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7448): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7318:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7318/cgroup.procs: No such file or directory
,I/CheckinService( 6798): Checkin interval check for package: unspecified last checkin: 1452278406473 min interval config: 0 actual interval: 4123
,I/CheckinService( 6798): Checkin interval check for package: unspecified last checkin: 1452278406473 min interval config: 0 actual interval: 4126
,I/CheckinService( 6798): Checking schedule, now: 1452278410608 next: 1452278436440
,I/CheckinService( 6798): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7468 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6798): Checking schedule, now: 1452278410662 next: 1452278436440
I/CheckinService( 6798): active receiver: disabled
,I/art     (  309): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 24.754ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.722ms
,W/ResourcesManager( 7468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.578ms
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Babel_SMS( 7468): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7468): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7468): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7468): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7468): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7468): MmsConfig.loadFromResources
E/Babel_SMS( 7468): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7468): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Launcher( 1568): Deferring update until onResume
,I/art     (  880): Explicit concurrent mark sweep GC freed 15758(779KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.732ms total 135.994ms
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@ee8be78
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 7468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7468): startup - clean
,I/Babel   ( 7468): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7506 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7468): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7468): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7468): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7468): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7468): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7468): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7468): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7468): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7468): onServiceConnected
W/Babel   ( 7468): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7506): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7506):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7506):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7468): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6896:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6896/cgroup.procs: No such file or directory
,W/GAv4    ( 7506): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7506): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7506): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7506): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7506): Time to load native libraries: 1 ms (timestamps 6320-6321)
I/LibraryLoader( 7506): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7506): Binding Chromium to main looper Looper (main, tid 1) {206bb932}
,I/LibraryLoader( 7506): Expected native library version number "",actual native library version number ""
,I/chromium( 7506): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7506): Initializing chromium process, singleProcess=true
,W/art     ( 7506): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7506): ApplicationContext is null in ApplicationStatus
,W/chromium( 7506): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7506): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7506): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7506): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7506): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7506): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7506): Local Branch: 
I/Adreno-EGL( 7506): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7506): Local Patches: NONE
I/Adreno-EGL( 7506): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7506): Starting up...
,W/AudioManagerAndroid( 7506): Requires BLUETOOTH permission
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7573 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7386:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7386/cgroup.procs: No such file or directory
I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7592 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7422:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7422/cgroup.procs: No such file or directory
,W/ResourcesManager( 7592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7612 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7358:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7612): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7448:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2613): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7358/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7448/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2613): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2613): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2613): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2613): onServiceConnected()
D/GetNotificationsWS( 2613): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2613): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2613): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2613): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2613): [debug] > In cancelAnyPendingIntentSetPreviously
,I/PushService( 2613): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,E/MDM     ( 1709): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/OtaApp  ( 2613): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2613): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2613): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 6798): Restart initialization of location
,D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/OtaApp  ( 2613): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2613): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2613): publish the event [tag = MOT_OTA event name = LOG]
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2613): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2613): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2613): publish the event [tag = MOT_OTA event name = LOG]
,W/GCoreFlp( 1709): No location to return for getLastLocation()
,W/FusedLocationProvider( 1709): location=null
,D/OtaApp  ( 2613): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2613): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2613): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7653 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator( 1418): onFinishInput()
,W/IInputConnectionWrapper( 6540): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7653): Register our PhoneStateListener
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
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,194
,V/SetupWizard( 7653): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 7468:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7468/cgroup.procs: No such file or directory
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7674 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7700 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7506:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7506/cgroup.procs: No such file or directory
,W/ResourcesManager( 7700): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7700): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7700): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7700): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7700): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7700): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7700): MmsConfig.loadFromResources
,E/Babel_SMS( 7700): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7700): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7700): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7700): startup - clean
,I/Babel   ( 7700): deleted: false for 0
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7733 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/VideoCapabilities( 7700): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7700): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7700): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7700): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7700): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7700): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7700): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7700): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 7573:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7573/cgroup.procs: No such file or directory
,I/vclib   ( 7700): onServiceConnected
,W/Babel   ( 7700): Attempted to change video mute state without an active call.
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7768 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7592:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7592/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7791 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7700): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/asset   ( 7791): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7791): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7791): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7791): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,V/JNIHelp ( 7700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7700): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7700): Installed default security provider GmsCore_OpenSSL
,I/art     (  880): Explicit concurrent mark sweep GC freed 14182(723KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.420ms total 114.888ms
,D/PackageBroadcastService( 6798): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7733): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd8233b new=com.google.android.velvet.VelvetApplication@3bd8233b
,I/PackageBroadcastService( 6798): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7824 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.493ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 448us total 23.659ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.751ms
,W/ResourcesManager( 7824): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 6798): Storage manager: low false usage 1.75MB avail 3.12GB capacity 4.85GB
,I/UpdateIcingCorporaServi( 7733): UpdateCorporaTask done [took 183 ms] updated apps [took 183 ms] 
,I/ActivityManager(  880): Killing 7674:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7674/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7862 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6798): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  880): Killing 7653:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7653/cgroup.procs: No such file or directory
,I/Icing   ( 6798): Internal init done: storage state 0
,D/Finsky  ( 7862): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 6798): Post-init done
,I/Icing   ( 6798): updateResources: need to parse f{com.google.android.gms}
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,D/Finsky  ( 7862): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7862): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7862): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7862): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 7862): Skipping gmscore version check
,D/Finsky  ( 7862): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  880): Killing 7768:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/art     ( 1709): Explicit concurrent mark sweep GC freed 106267(5MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 15MB/25MB, paused 1.384ms total 116.667ms
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7768/cgroup.procs: No such file or directory
,D/Finsky  ( 7862): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7862): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c53a615)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15764d2a)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@75dd71b)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@346100b8)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21d58e91)
,I/Icing   ( 6798): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6798): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6798): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310899, SEQNUM=4486, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-379, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2467): Disconnected process message: 10, size: 0
,I/ActivityManager(  880): Killing 7791:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7791/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7700:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7700/cgroup.procs: No such file or directory
,I/CheckinService( 6798): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311541, SEQNUM=4492, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-397, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2467): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1709): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {3207969d, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): send {176bcae3, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {3207969d, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
,V/AlarmManager(  880): done {176bcae3, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [24ms]
,I/CheckinService( 6798): Checkin interval check for package: unspecified last checkin: 1452278406473 min interval config: 0 actual interval: 37932
,I/CheckinService( 6798): Checking schedule, now: 1452278444418 next: 1452278436440
I/CheckinService( 6798): active receiver: enabled
,I/CheckinService( 6798): Preparing to send checkin request
I/EventLogService( 6798): Accumulating logs since 1452278400985
,I/CheckinRequestBuilder( 6798): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6798): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7937 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7937): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7937): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7937): VM with version 2.1.0 has multidex support
I/MultiDex( 7937): install
I/MultiDex( 7937): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7937): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7937): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7937): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7937): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/MDM     ( 1709): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 6798): Restart initialization of location
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1709): No location to return for getLastLocation()
W/FusedLocationProvider( 1709): location=null
,I/art     ( 7937): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7937): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7937): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
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
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb13a0960
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb79fbd20, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79091c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a06d78, idLength=0xbece32b0
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
D/WVCdm   (  296): PrepareKeyRequest: nonce=1237087871
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb792cf40
D/DrmWidevineDash(  296): message_length=1591, signature=0xb793ddd8, signature_length=3201184404
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faf000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb548a960
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1,
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb79fbe98, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79091c8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a06d98, idLength=0xbece32b0
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=756715120
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb79091c8
D/DrmWidevineDash(  296): message_length=1626, signature=0xb793ddd8, signature_length=3201184404
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  296): L3 Terminate.
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7980): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7980): dex2oat took 76.766ms (threads: 4)
,I/Adreno-EGL( 7937): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7937): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7937): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7937): Local Branch: 
I/Adreno-EGL( 7937): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7937): Local Patches: NONE
I/Adreno-EGL( 7937): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7937): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7937): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7937): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7937): Local Branch: 
I/Adreno-EGL( 7937): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7937): Local Patches: NONE
I/Adreno-EGL( 7937): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7937): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7937): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7937): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7937): Local Branch: 
I/Adreno-EGL( 7937): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7937): Local Patches: NONE
I/Adreno-EGL( 7937): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7937): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7937): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7937): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7937): Local Branch: 
I/Adreno-EGL( 7937): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7937): Local Patches: NONE
I/Adreno-EGL( 7937): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6798): Classify the device as Phone.
,I/CheckinTask( 6798): Sending checkin request (9607 bytes)
,I/CheckinRequestBuilder( 6798): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6798): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6798): Classify the device as Phone.
,I/CheckinTask( 6798): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6798): Checking schedule, now: 1452278448284 next: 1452879585272
I/CheckinService( 6798): active receiver: disabled
,D/CheckinService( 6798): Recording last checkin time for package unspecified as 1452278448295
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7998 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7998): Register our PhoneStateListener
,V/SetupWizard( 7998): Connected to Gservices successfully
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 7612:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7733:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7612/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7733/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8021 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Launcher( 1568): Deferring update until onResume
,I/art     (  880): Explicit concurrent mark sweep GC freed 20162(1017KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.668ms total 124.765ms
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a2961d
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8062 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8079 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7824:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7862:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7824/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7862/cgroup.procs: No such file or directory
,W/ResourcesManager( 8079): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8079): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8079): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8079): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8079): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8079): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8079): MmsConfig.loadFromResources
E/Babel_SMS( 8079): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8079): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8079): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8079): startup - clean
,I/Babel   ( 8079): deleted: false for 0
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8108 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8079): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8079): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8079): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8079): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8079): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8079): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8079): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8079): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8127 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7998:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8108): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7998/cgroup.procs: No such file or directory
,W/asset   ( 8127): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8127): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8127): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8127): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6798): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6798): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8021): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd8233b new=com.google.android.velvet.VelvetApplication@3bd8233b
,I/Icing   ( 6798): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8160 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 8079): onServiceConnected
,W/Babel   ( 8079): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8079): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8079): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8160): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 8021): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,V/JNIHelp ( 8079): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8079): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8079): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8188 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7937:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7937/cgroup.procs: No such file or directory
,D/Finsky  ( 8188): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8188): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8188): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8188): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8188): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8188): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8188): Skipping gmscore version check
,D/Finsky  ( 8188): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8188): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8062:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8062/cgroup.procs: No such file or directory
,I/Icing   ( 6798): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6798): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8127:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8127/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 8021:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8021/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1418): run()
I/Keyboard.Facilitator( 1418): flushDynamicLanguageModels()
,I/ConfigService( 1709): onCreate
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310554, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-456, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2467): Disconnected process message: 10, size: 0
,I/ConfigService( 1709): onDestroy
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6540): --= Surplus to requirements =--
I/jxcore-log( 6540): 
I/jxcore-log( 6540): ****TEST TOOK:  ms ****
I/jxcore-log( 6540): 
I/jxcore-log( 6540): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6540): 
,D/AndroidRuntime( 8255): 
D/AndroidRuntime( 8255): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8255): CheckJNI is OFF
,D/AndroidRuntime( 8255): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.test.thalitest appid=10427 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6540:com.test.thalitest/u0a427 (adj 9): stop com.test.thalitest
,W/PackageSettings(  880): Skipping PackageSetting{1eb878b6 com.example.hello/10426} due to missing metadata
,I/WindowState(  880): WIN DEATH: Window{2423bcac u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  880): Client connection lost with reason: 4
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{27a37d38 u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  880): Spurious death for ProcessRecord{3b4fe91c 6540:com.test.thalitest/u0a427}, curProc for 6540: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10427 user=0: pkg removed
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{27a37d38 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{27a37d38 u0 com.test.thalitest/.MainActivity t3 f}
,W/GeofencerStateMachine( 1709): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1418): resetDictionaries() : en_US
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 3040): Explicit concurrent mark sweep GC freed 9303(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 7MB/12MB, paused 1.220ms total 54.943ms
,I/Keyboard.Facilitator.DecoderInitializer( 1418): run()
,I/Decoder ( 1418): createOrResetDecoder
,D/VoicemailCleanupService( 8108): Cleaning up data for package: com.test.thalitest
,I/art     ( 1568): Explicit concurrent mark sweep GC freed 5053(311KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 584us total 93.042ms
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8294 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.345ms
,I/ConfigService( 1709): onCreate
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.028ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 17892(1177KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.716ms total 185.315ms
,I/art     (  880): WaitForGcToComplete blocked for 103.927ms for cause Explicit
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.611ms
,W/asset   ( 8294): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8294): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8294): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8294): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1418): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1418): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1418): run()
I/StatsUtilsManager( 1418): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1418): shouldRecordStats() = Too Soon
,I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8318 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
,I/ActivityManager(  880): Killing 8079:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     (  880): Explicit concurrent mark sweep GC freed 5773(308KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.225ms total 209.670ms
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_8079/cgroup.procs: No such file or directory
,I/Launcher( 1568): Deferring update until onResume
,W/ContextImpl( 8318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6798): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6798): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6798): Reading stored module config
,D/AndroidRuntime( 8255): Shutting down VM
,D/ChimeraCfgMgr( 6798): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6798): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6798): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6798): App measurement is starting up, version: 8489
I/GMPM-SVC( 6798): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1709): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1709): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6798): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6798): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6798): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6798): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8351 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 6798): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6798): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6798): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Icing   ( 6798): doRemovePackageData com.test.thalitest
,D/ChimeraCfgMgr( 6798): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6798): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 6798): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 6798): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6798): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6798): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6798): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6798): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6798): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd8233b new=com.google.android.velvet.VelvetApplication@3bd8233b
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8385 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/SQLiteLog( 6798): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/BaseAppContext( 6798): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,--------- beginning of crash
E/AndroidRuntime( 6798): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6798): Process: com.google.android.gms, PID: 6798
E/AndroidRuntime( 6798): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6798): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6798): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6798): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6798): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6798): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6798): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.c.f.b(SourceFile:3345)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.c.f.b(SourceFile:787)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6798): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6798): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6798): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6798): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BaseAppContext( 6798): Using Auth Proxy for data requests.
W/BaseAppContext( 6798): Using Auth Proxy for data requests.
W/BaseAppContext( 6798): Using Auth Proxy for data requests.
I/Process ( 6798): Sending signal. PID: 6798 SIG: 9
,D/WifiService(  880): Client connection lost with reason: 4
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8420 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Process com.google.android.gms (pid 6798) has died
,W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10999ms
,I/UpdateIcingCorporaServi( 8351): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/native  ( 1418): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1418): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1418): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1418): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1418): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1418): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/SQLiteDatabase( 8351): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 8351): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 8351): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 8351): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8351): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/SQLiteDatabase( 8351): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 8351): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/SQLiteDatabase( 8351): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/SQLiteDatabase( 8351): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8351): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8351): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8351): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=8440 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SharedPreferencesImpl( 8351): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
,E/AndroidRuntime( 8351): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 8351): Process: com.google.android.googlequicksearchbox:search, PID: 8351
E/AndroidRuntime( 8351): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 8351): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 8351): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8351): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/AndroidRuntime( 8351): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 8351): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 8351): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 8351): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8351): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8351): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8351): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/Process ( 8351): Sending signal. PID: 8351 SIG: 9

```
