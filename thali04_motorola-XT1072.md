#### Test 561510933390750_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  885): send {22cd5911, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  885): done {22cd5911, *walarm*:com.google.android.intent.action.SEND_IDLE} [13ms]
--------- beginning of main
D/AndroidRuntime( 6522): 
D/AndroidRuntime( 6522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6522): CheckJNI is OFF
D/AndroidRuntime( 6522): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6541 uid=10455 gids={50455, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6522): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6541): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6541): Time to load native libraries: 1 ms (timestamps 5954-5955)
I/LibraryLoader( 6541): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6541): Binding Chromium to main looper Looper (main, tid 1) {1ddbacb4}
,I/LibraryLoader( 6541): Expected native library version number "",actual native library version number ""
,I/chromium( 6541): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6541): Initializing chromium process, singleProcess=true
,W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6541): ApplicationContext is null in ApplicationStatus
,W/chromium( 6541): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6541): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6541): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6541): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6541): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6541): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6541): Local Branch: 
I/Adreno-EGL( 6541): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6541): Local Patches: NONE
I/Adreno-EGL( 6541): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a110105:true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{16b84a76 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6541): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6541): CordovaWebView is running on device made by: motorola
,E/global frequency( 2609): no tags to log
D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1544): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/OpenGLRenderer( 6541): Render dirty regions requested: true
,D/Atlas   ( 6541): Validating map...
,W/chromium( 6541): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/art     (  885): Explicit concurrent mark sweep GC freed 37774(1770KB) AllocSpace objects, 2(234KB) LOS objects, 33% free, 20MB/30MB, paused 1.631ms total 127.443ms
,I/OpenGLRenderer( 6541): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6541): Enabling debug mode 0
,I/Keyboard.Facilitator( 1421): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1068
,I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +1s2ms (total +1s68ms)
,W/IInputConnectionWrapper( 6541): showStatusIcon on inactive InputConnection
,I/art     ( 2609): Explicit concurrent mark sweep GC freed 36298(2MB) AllocSpace objects, 7(135KB) LOS objects, 40% free, 11MB/19MB, paused 1.101ms total 86.808ms
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/Adreno-ES20( 6541): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6541): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1544): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/BindingManager( 6541): Cannot call determinedVisibility() - never saw a connection for the pid: 6541
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 57159(3MB) AllocSpace objects, 37(1303KB) LOS objects, 39% free, 7MB/12MB, paused 747us total 48.004ms
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1544): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/JsMessageQueue( 6541): Set native->JS mode to OnlineEventsBridgeMode
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2609): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2609): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2609): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2609): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2609): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/jxcore_app_log( 6541): JniHelper::setJavaVM(0xb7c17310), pthread_self() = -1208326552
,D/JX-Cordova( 6541): jxcore cordova android initializing
,W/jxcore-log( 6541): Initializing JXcore engine
W/jxcore-log( 6541): JXcore engine is ready
,W/jxcore-log( 6541): Starting JXcore engine
,I/art     ( 6541): Background sticky concurrent mark sweep GC freed 46392(4MB) AllocSpace objects, 0(0B) LOS objects, 12% free, 23MB/26MB, paused 5.466ms total 108.329ms
,W/.test.thalitest( 6541): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10455 path="socket:[9500]" dev="sockfs" ino=9500 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6541): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10455 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6541): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10455 path="socket:[9611]" dev="sockfs" ino=9611 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6541): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10455 path="socket:[30382]" dev="sockfs" ino=30382 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6541): Platform android
W/jxcore-log( 6541): 
W/jxcore-log( 6541): Process ARCH arm
W/jxcore-log( 6541): 
,I/jxcore-log( 6541): JXcore Cordova bridge is ready!
I/jxcore-log( 6541): 
W/jxcore-log( 6541): JXcore engine is started
I/chromium( 6541): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6541): Toggling radios to true
I/jxcore-log( 6541): 
,D/BluetoothAdapter( 6541): enable(): BT is already enabled..!
,D/WifiService(  885): New client listening to asynchronous messages
,D/WifiService(  885): setWifiEnabled: true pid=6541, uid=10455
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6541): Radios toggled
I/jxcore-log( 6541): 
,I/jxcore-log( 6541): My device name is: motorola-XT1072
I/jxcore-log( 6541): 
,I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
,I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering(  885): InitialState.processMessage what=4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 21
D/TCMD    (  481): Listening for incoming client connection request
,V/NativeCrypto( 1744): Read error: ssl=0xb7e8f1f0: I/O error during system call, Connection timed out
E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
,V/NativeCrypto( 1744): SSL shutdown failed: ssl=0xb7e8f1f0: I/O error during system call, Broken pipe
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/WifiMetrics(  885): connected time updated 131078
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6629 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1528): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/ModemStatsDSDetect( 1528): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
W/ResourcesManager( 6629): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6655 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6368:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6368/cgroup.procs: No such file or directory
,W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  481): NL - Read 56 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1417): wlan0: Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1417): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  885): [1,453,032,883,222 ms] noteScanEnd no scan source
E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3c268428 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  481): NL - Read 312 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 192 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
I/wpa_supplicant( 1417): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1417): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
,I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1205654096
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
E/Tethering(  885): ApnList is empty for checkDunConfigured()
,D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  292): Setting iface cfg
,E/WifiStateMachine(  885): Start Dhcp Watchdog 2
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  885): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@581e6a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@581e6a0 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6655): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6655): MmsConfig.loadMmsSettings
I/Babel_SMS( 6655): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6655): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6655): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6655): MmsConfig.loadFromResources
,E/Babel_SMS( 6655): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6655): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6655): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6655): startup - clean
,I/Babel   ( 6655): deleted: false for 0
,E/DHCPCD  ( 6701): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6701): version 5.5.6 starting
,E/DHCPCD  ( 6701): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6701): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6701): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6701): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6701): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6701): wlan0: sending REQUEST (xid 0xfde656c6), next in 4.29 seconds
,W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6655): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6655): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6655): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  885): Killing 6208:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6208/cgroup.procs: No such file or directory
,I/vclib   ( 6655): onServiceConnected
W/Babel   ( 6655): Attempted to change video mute state without an active call.
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DHCPCD  ( 6701): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6701): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6701): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6701): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 20
D/TCMD    (  481): Listening for incoming client connection request
D/DHCPCD  ( 6701): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6701): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/DHCPCD  ( 6701): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/ModemStatsDSDetect( 1528): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
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
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 12:14:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453032885449], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453032885429]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
,D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1528): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1528): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1470): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6764 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1470): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1470): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2609): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2609): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2609): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2609): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2609): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2609): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2609): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2609): [debug] > CusSM.onRadioDown
,I/MusicStore( 6764): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6764): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6764): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6764): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6764): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6764): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6764): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6764): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6764): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f4c0e10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6764): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6764): GMSCore installation verified
,I/ConfigStore( 6764): Config Database version: 1
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/art     (  885): Explicit concurrent mark sweep GC freed 46729(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.796ms total 137.736ms
,I/MediaRouter( 6764): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6764): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6764): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6764): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6806 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.435ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.258ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 26.155ms
,I/GHttpClientFactory( 6764): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6764): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6426:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_6426/cgroup.procs: No such file or directory
,V/Mms     ( 6806): mnc/mcc: 
V/Mms     ( 6806): tag: int value: recipientLimit - 20
V/Mms     ( 6806): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6806): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6806): tag: int value: maxSubjectLength - 80
V/Mms     ( 6806): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6806): tag: bool value: enableGroupMms - false
V/Mms     ( 6806):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6806): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6847 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6236:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6847): Register our PhoneStateListener
,I/jxcore-log( 6541): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6541): 
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6236/cgroup.procs: No such file or directory
,I/jxcore-log( 6541): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6541): 
,D/MobileConnectivityChangeReceiver( 6847): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6847): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6655:com.google.android.talk/u0a70 (adj 15): empty #7
,I/jxcore-log( 6541): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6541): 
,I/jxcore-log( 6541): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6541): 
,I/jxcore-log( 6541): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6541): 
,I/jxcore-log( 6541): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6541): 
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6655/cgroup.procs: No such file or directory
,I/CheckinService( 6280): Checkin interval check for package: unspecified last checkin: 1453032797973 min interval config: 0 actual interval: 89662
,I/CheckinService( 6280): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6280): SYNC; picasa accounts
,I/CheckinService( 6280): Checking schedule, now: 1453032887670 next: 1453032827950
I/CheckinService( 6280): active receiver: enabled
,D/NetworkLogImpl( 6280): Loaded NetworkSpeedPredictor
,I/CheckinService( 6280): Preparing to send checkin request
,I/iu.Environment( 6280): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6280): num queued entries: 0
I/iu.UploadsManager( 6280): num updated entries: 0
,I/EventLogService( 6280): Accumulating logs since 1453032794831
,I/iu.SyncManager( 6280): NEXT; no task
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6874 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6280): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
,E/ActivityThread( 6280): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6898 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/jxcore-log( 6541): Test app app.js loaded
I/jxcore-log( 6541): 
,I/chromium( 6541): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): now: 206208 ,futureTime: 9223372036854775807
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): now: 206208 ,futureTime: 9223372036854775807
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): now: 206208 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1470): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2609): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2609): [debug] > PollingManagerService, now: 206211 ,futureTime: 20987900
D/OtaApp  ( 2609): [debug] > Polling alarm set to expire at: 20987900 Current Time: 206212
,D/Central_PollingManager( 1470): now: 206214 ,futureTime: 86476229
D/Central_PollingManager( 1470): Polling alarm set to expire at: 86476229 Current Time: 206214
,D/OtaApp  ( 2609): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2609): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2609): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/NetworkMonitor( 6764): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2609): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2609): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 4908(218KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 864us total 29.324ms
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6919 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,I/Babel_SMS( 6898): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6898): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6898): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6898): MmsConfig.loadFromDatabase
,W/ResourcesManager( 6919): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6919): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 6898): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6898): MmsConfig.loadFromResources
,E/Babel_SMS( 6898): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6898): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 6919): VM with version 2.1.0 has multidex support
I/MultiDex( 6919): install
,I/MultiDex( 6919): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6919): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6898): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6898): startup - clean
,I/Babel   ( 6898): deleted: false for 0
,W/ActivityThread( 6919): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6919): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e0649f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6919): Installed default security provider GmsCore_OpenSSL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
I/art     ( 6919): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6919): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6948 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6919): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 6898): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6898): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6898): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6898): Unsupported profile 4 for video/mp4v-es
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/VideoCapabilities( 6898): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6898): Unrecognized profile 2130706433 for video/avc
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 6898): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
W/VideoCapabilities( 6898): Unrecognized profile 2130706433 for video/avc
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb0ea5960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8d6a2c8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d72e40, wrapped_rsa_key_length=1280
I/vclib   ( 6898): onServiceConnected
W/Babel   ( 6898): Attempted to change video mute state without an active call.
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ea2dd0, idLength=0xbe96a2b0
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  296): PrepareKeyRequest: nonce=436561118
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8dbad18
D/DrmWidevineDash(  296): message_length=1591, signature=0xb8e57a08, signature_length=3197543060
,I/Babel   ( 6898): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  885): Killing 6629:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6629/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6948): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6948): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6948): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6948): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6948): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6948):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6948):   adb logcat -s GAv4
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb54b8960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8dbffb8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d72e40, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ea2e10, idLength=0xb13f2730
,I/art     (  885): Explicit concurrent mark sweep GC freed 12732(626KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 3.493ms total 139.544ms
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
W/GAv4    ( 6948): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2917143921
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8d68d28
D/DrmWidevineDash(  296): message_length=1626, signature=0xb8e57b00, signature_length=2973706004
,W/GAv4    ( 6948): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6948): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
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
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 6948): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6948): Time to load native libraries: 1 ms (timestamps 7676-7677)
I/LibraryLoader( 6948): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6948): Binding Chromium to main looper Looper (main, tid 1) {266c9161}
,I/LibraryLoader( 6948): Expected native library version number "",actual native library version number ""
,I/chromium( 6948): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6948): Initializing chromium process, singleProcess=true
,W/art     ( 6948): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6948): ApplicationContext is null in ApplicationStatus
,W/chromium( 6948): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6948): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6948): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6948): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6948): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6948): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6948): Local Branch: 
I/Adreno-EGL( 6948): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6948): Local Patches: NONE
I/Adreno-EGL( 6948): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 7007): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 6948): Requires BLUETOOTH permission
,I/NSApplication( 6948): Starting up...
,V/AlarmManager(  885): send {248afbef, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7025 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6764:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 7007): dex2oat took 124.852ms (threads: 4)
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6764/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6919): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6919): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6919): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6919): Local Branch: 
I/Adreno-EGL( 6919): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6919): Local Patches: NONE
I/Adreno-EGL( 6919): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6919): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6919): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6919): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6919): Local Branch: 
I/Adreno-EGL( 6919): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6919): Local Patches: NONE
I/Adreno-EGL( 6919): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6919): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6919): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6919): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6919): Local Branch: 
I/Adreno-EGL( 6919): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6919): Local Patches: NONE
I/Adreno-EGL( 6919): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6919): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6919): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6919): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6919): Local Branch: 
I/Adreno-EGL( 6919): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6919): Local Patches: NONE
I/Adreno-EGL( 6919): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7045 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6806:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6806/cgroup.procs: No such file or directory
,W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6280): Classify the device as Phone.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7070 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7094 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6874:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7070): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 6847:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6874/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6847/cgroup.procs: No such file or directory
,I/MusicStore( 7094): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7094): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7094): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7094): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7094): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7094): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7094): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7094): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7094): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f4c0e10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7094): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7094): GMSCore installation verified
,I/ConfigStore( 7094): Config Database version: 1
,I/MediaRouter( 7094): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7094): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7094): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7094): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7140 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 3214): Explicit concurrent mark sweep GC freed 1523(54KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 413us total 31.916ms
,I/GHttpClientFactory( 7094): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7094): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6898:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7140): mnc/mcc: 
V/Mms     ( 7140): tag: int value: recipientLimit - 20
V/Mms     ( 7140): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7140): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7140): tag: int value: maxSubjectLength - 80
V/Mms     ( 7140): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7140): tag: bool value: enableGroupMms - false
V/Mms     ( 7140):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6898/cgroup.procs: No such file or directory
,W/ResourcesManager( 7140): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7171 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 24.323ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.491ms
,I/ActivityManager(  885): Killing 6948:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 21.098ms
,I/CheckinTask( 6280): Sending checkin request (9503 bytes)
,D/PhoneMonitor( 7171): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_6948/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7171): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7171): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7025:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7025/cgroup.procs: No such file or directory
,I/CheckinService( 6280): Checkin interval check for package: unspecified last checkin: 1453032797973 min interval config: 0 actual interval: 93978
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7190 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7210 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7045:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/CheckinRequestBuilder( 6280): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7045/cgroup.procs: No such file or directory
,E/ActivityThread( 6280): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7210): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  885): Explicit concurrent mark sweep GC freed 8732(423KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.526ms total 122.047ms
,I/Babel_SMS( 7210): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7210): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7210): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7210): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7210): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7210): MmsConfig.loadFromResources
,E/Babel_SMS( 7210): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7210): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CheckinRequestBuilder( 6280): Classify the device as Phone.
,I/CheckinTask( 6280): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6280): Checking schedule, now: 1453032892661 next: 1453634029654
I/CheckinService( 6280): active receiver: disabled
,I/CheckinService( 6280): Checking schedule, now: 1453032892691 next: 1453634029654
I/CheckinService( 6280): active receiver: disabled
,D/CheckinService( 6280): Recording last checkin time for package unspecified as 1453032892694
,I/ActivityManager(  885): Killing 7070:android.process.acore/u0a7 (adj 15): empty #7
,W/Settings( 7210): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7210): startup - clean
,I/Babel   ( 7210): deleted: false for 0
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7070/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7251 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7094:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7094/cgroup.procs: No such file or directory
,W/VideoCapabilities( 7210): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7210): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7210): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7210): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7210): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7210): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7210): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7210): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7210): onServiceConnected
W/Babel   ( 7210): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7251): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7251): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7251): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7251):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7251):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7251): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7251): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7251): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7210): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7140:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7251): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7251): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7140/cgroup.procs: No such file or directory
,I/WebViewFactory( 7251): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7251): Time to load native libraries: 1 ms (timestamps 1320-1321)
I/LibraryLoader( 7251): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7251): Binding Chromium to main looper Looper (main, tid 1) {266c9161}
,I/LibraryLoader( 7251): Expected native library version number "",actual native library version number ""
,I/chromium( 7251): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7251): Initializing chromium process, singleProcess=true
W/art     ( 7251): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7251): ApplicationContext is null in ApplicationStatus
,W/chromium( 7251): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7251): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7251): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7251): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7251): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7251): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7251): Local Branch: 
I/Adreno-EGL( 7251): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7251): Local Patches: NONE
I/Adreno-EGL( 7251): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7251): Starting up...
,W/AudioManagerAndroid( 7251): Requires BLUETOOTH permission
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7317 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7171:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7171/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7336 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7190:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7190/cgroup.procs: No such file or directory
,W/ResourcesManager( 7336): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7356 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7251:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7356): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7210:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7251/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2609): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7210/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2609): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2609): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2609): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2609): onServiceConnected()
,D/GetNotificationsWS( 2609): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2609): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7390 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2609): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7416 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6919:com.google.android.gms.unstable/u0a16 (adj 13): empty #7
,I/MusicStore( 7416): Database version: 120
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6919/cgroup.procs: No such file or directory
W/ActivityManager(  885): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7416): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7416): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7416): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7416): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7416): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7416): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7416): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7416): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f4c0e10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7416): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7416): GMSCore installation verified
,I/ConfigStore( 7416): Config Database version: 1
,I/MediaRouter( 7416): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7416): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7416): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7416): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7447 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7416): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7416): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 7317:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7447): mnc/mcc: 
,V/Mms     ( 7447): tag: int value: recipientLimit - 20
V/Mms     ( 7447): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7447): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7447): tag: int value: maxSubjectLength - 80
V/Mms     ( 7447): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7447): tag: bool value: enableGroupMms - false
,V/Mms     ( 7447):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7317/cgroup.procs: No such file or directory
,W/ResourcesManager( 7447): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7473 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7336:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7473): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7336/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7473): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7473): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6280): Checkin interval check for package: unspecified last checkin: 1453032892694 min interval config: 0 actual interval: 2927
,I/CheckinService( 6280): Checkin interval check for package: unspecified last checkin: 1453032892694 min interval config: 0 actual interval: 2939
,I/CheckinService( 6280): Checking schedule, now: 1453032895637 next: 1453032922654
I/CheckinService( 6280): active receiver: disabled
,I/CheckinService( 6280): Checking schedule, now: 1453032895651 next: 1453032922654
I/CheckinService( 6280): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7493 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 22.513ms
,I/ActivityManager(  885): Killing 7356:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.767ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.737ms
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7356/cgroup.procs: No such file or directory
,I/art     (  885): Explicit concurrent mark sweep GC freed 12300(628KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.486ms total 113.694ms
,W/ResourcesManager( 7493): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7493): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7493): MmsConfig.loadMmsSettings
I/Babel_SMS( 7493): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7493): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7493): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7493): MmsConfig.loadFromResources
,E/Babel_SMS( 7493): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7493): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7493): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7493): startup - clean
,I/Babel   ( 7493): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7524 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7493): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7493): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7493): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7493): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7493): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7493): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7493): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7493): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7493): onServiceConnected
,W/Babel   ( 7493): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7524): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
I/Babel   ( 7493): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7416:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/ContextImpl( 7524): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7524): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7524):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7524):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7524): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7524): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7416/cgroup.procs: No such file or directory
,W/GAv4    ( 7524): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7524): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7524): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7524): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7524): Time to load native libraries: 1 ms (timestamps 4707-4708)
I/LibraryLoader( 7524): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7524): Binding Chromium to main looper Looper (main, tid 1) {266c9161}
,I/LibraryLoader( 7524): Expected native library version number "",actual native library version number ""
I/chromium( 7524): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7524): Initializing chromium process, singleProcess=true
W/art     ( 7524): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7524): ApplicationContext is null in ApplicationStatus
,W/chromium( 7524): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7524): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7524): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7524): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7524): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7524): Local Branch: 
I/Adreno-EGL( 7524): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7524): Local Patches: NONE
I/Adreno-EGL( 7524): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7524): Requires BLUETOOTH permission
,I/NSApplication( 7524): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7593 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7447:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7447/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7612 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7473:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7473/cgroup.procs: No such file or directory
,W/ResourcesManager( 7612): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7635 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7493:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7635): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7390:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7493/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2609): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7390/cgroup.procs: No such file or directory
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,D/GetNotificationsWS( 2609): bindWebServices(): registering our AIDL callback...
I/SundryService( 2609): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2609): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2609): onServiceConnected()
,D/GetNotificationsWS( 2609): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2609): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2609): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2609): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2609): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2609): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2609): [debug] > DownloadActivity, FormattedText
,D/WearableService( 1744): callingUid 10016, callindPid: 1744
,I/OtaApp  ( 2609): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2609): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2609): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1744): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6280): Restart initialization of location
,D/OtaApp  ( 2609): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2609): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,E/MDM     ( 1744): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2609): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2609): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Keyboard.Facilitator( 1421): onFinishInput()
,W/IInputConnectionWrapper( 6541): showStatusIcon on inactive InputConnection
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7677 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1744): No location to return for getLastLocation()
,W/FusedLocationProvider( 1744): location=null
I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/AlarmManager(  885): done {248afbef, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8033ms]
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,182
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3d63562
,I/GCoreNlp( 1744): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7704 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7704): Register our PhoneStateListener
,V/SetupWizard( 7704): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 7524:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7524/cgroup.procs: No such file or directory
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7727 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7749 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7766 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7593:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7612:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7593/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7612/cgroup.procs: No such file or directory
,W/ResourcesManager( 7766): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  885): Explicit concurrent mark sweep GC freed 19250(969KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.892ms total 118.591ms
,I/Babel_SMS( 7766): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7766): MmsConfig.loadMmsSettings
I/Babel_SMS( 7766): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7766): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7766): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7766): MmsConfig.loadFromResources
,E/Babel_SMS( 7766): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7766): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7766): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7766): startup - clean
,I/Babel   ( 7766): deleted: false for 0
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7803 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7766): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7766): Unsupported mime audio/amr-wb-plus
,W/asset   ( 7803): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7803): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7803): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7803): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7766): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7766): Unsupported profile 4 for video/mp4v-es
,D/PackageBroadcastService( 6280): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6280): Null package name or gms related package.  Ignoreing.
,W/VideoCapabilities( 7766): Unrecognized profile 2130706433 for video/avc
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b2b439e new=com.google.android.velvet.VelvetApplication@3b2b439e
,I/UpdateIcingCorporaServi( 7727): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/VideoCapabilities( 7766): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7766): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 6280): updateResources: need to parse f{com.google.android.gms}
W/VideoCapabilities( 7766): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7830 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.625ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 19.405ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.540ms
,W/ResourcesManager( 7830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7766): onServiceConnected
,W/Babel   ( 7766): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7766): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7766): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7727): UpdateCorporaTask done [took 177 ms] updated apps [took 177 ms] 
,I/ActivityManager(  885): Killing 7677:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7766): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7677/cgroup.procs: No such file or directory
,W/System  ( 7766): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7766): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7861 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7704:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7704/cgroup.procs: No such file or directory
,D/Finsky  ( 7861): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7861): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7861): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7861): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7861): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7861): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7861): Skipping gmscore version check
,D/Finsky  ( 7861): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7861): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Killing 7749:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_7749/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 6280): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,V/AlarmManager(  885): send {1f2967a0, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {3015057a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7912 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/Icing   ( 6280): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,V/AlarmManager(  885): done {1f2967a0, *alarm*:android.intent.action.TIME_TICK} [91ms]
,I/GAv4    ( 7912): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7912):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7912):   adb logcat -s GAv4
,W/GAv4    ( 7912): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7912): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7912): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {3015057a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [324ms]
I/ActivityManager(  885): Killing 7803:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_7803/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7727:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_7727/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7635:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7635/cgroup.procs: No such file or directory
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310452, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-315, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/CheckinService( 6280): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310263, SEQNUM=4481, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-323, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  885): send {34ccffde, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  885): send {16fab12b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  885): done {34ccffde, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
V/AlarmManager(  885): done {16fab12b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,I/CheckinService( 6280): Checkin interval check for package: unspecified last checkin: 1453032892694 min interval config: 0 actual interval: 41472
,I/CheckinService( 6280): Checking schedule, now: 1453032934178 next: 1453032922654
I/CheckinService( 6280): active receiver: enabled
,I/CheckinService( 6280): Preparing to send checkin request
I/EventLogService( 6280): Accumulating logs since 1453032887919
,I/CheckinRequestBuilder( 6280): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6280): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7981 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7981): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7981): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7981): VM with version 2.1.0 has multidex support
I/MultiDex( 7981): install
I/MultiDex( 7981): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7981): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7981): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7981): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e0649f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7981): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1744): callingUid 10016, callindPid: 1744
,D/LocationInitializer( 6280): Restart initialization of location
,D/AuthorizationBluetoothService( 1744): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1744): [230] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1744): No location to return for getLastLocation()
W/FusedLocationProvider( 1744): location=null
,I/art     ( 7981): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7981): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7981): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
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
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbe96a4e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8ddc708, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d5c800, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ea2df0, idLength=0xb13f2730
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
D/WVCdm   (  296): PrepareKeyRequest: nonce=274174499
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8db6010
D/DrmWidevineDash(  296): message_length=1591, signature=0xb8dc0928, signature_length=2973706004
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb54b8960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8db2a30, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d5c800, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ea2e10, idLength=0xb0ea5730
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
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=3721135985
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8db6010
D/DrmWidevineDash(  296): message_length=1626, signature=0xb8dc0948, signature_length=2968147732
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8023): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8023): dex2oat took 81.301ms (threads: 4)
,I/Adreno-EGL( 7981): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7981): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7981): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7981): Local Branch: 
I/Adreno-EGL( 7981): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7981): Local Patches: NONE
I/Adreno-EGL( 7981): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7981): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7981): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7981): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7981): Local Branch: 
I/Adreno-EGL( 7981): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7981): Local Patches: NONE
I/Adreno-EGL( 7981): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7981): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7981): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7981): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7981): Local Branch: 
I/Adreno-EGL( 7981): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7981): Local Patches: NONE
I/Adreno-EGL( 7981): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7981): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7981): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7981): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7981): Local Branch: 
I/Adreno-EGL( 7981): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7981): Local Patches: NONE
I/Adreno-EGL( 7981): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6280): Classify the device as Phone.
,I/CheckinTask( 6280): Sending checkin request (9509 bytes)
,I/CheckinRequestBuilder( 6280): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6280): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  885): Explicit concurrent mark sweep GC freed 15458(760KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.519ms total 120.500ms
,I/CheckinRequestBuilder( 6280): Classify the device as Phone.
,I/CheckinTask( 6280): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6280): Checking schedule, now: 1453032937245 next: 1453634074236
I/CheckinService( 6280): active receiver: disabled
,D/CheckinService( 6280): Recording last checkin time for package unspecified as 1453032937262
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8043 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8043): Register our PhoneStateListener
,V/SetupWizard( 8043): Connected to Gservices successfully
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ClearcutLoggerApiImpl( 1744): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  885): Killing 7861:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  885): Killing 7830:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_7861/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7830/cgroup.procs: No such file or directory
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8073 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@5e53d8
,I/GCoreNlp( 1744): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8102 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8122 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7912:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10055/pid_7912/cgroup.procs: No such file or directory
,W/ResourcesManager( 7766): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7766): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8122): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8146 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8043:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8043/cgroup.procs: No such file or directory
,W/asset   ( 8146): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8146): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8146): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8146): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6280): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6280): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b2b439e new=com.google.android.velvet.VelvetApplication@3b2b439e
,I/UpdateIcingCorporaServi( 8073): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6280): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8173 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8173): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8073): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8197 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7981:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_7981/cgroup.procs: No such file or directory
,D/Finsky  ( 8197): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8197): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8197): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8197): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8197): Skipping gmscore version check
D/Finsky  ( 8197): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8197): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8197): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8197): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Killing 8102:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8102/cgroup.procs: No such file or directory
,I/Icing   ( 6280): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6280): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 8146:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_8146/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  885): Killing 7766:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7766/cgroup.procs: No such file or directory
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
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
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
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
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ConfigService( 1744): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1744): onDestroy
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310172, SEQNUM=4499, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-355, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6541): --= Surplus to requirements =--
I/jxcore-log( 6541): 
I/jxcore-log( 6541): ****TEST TOOK:  ms ****
I/jxcore-log( 6541): 
I/jxcore-log( 6541): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6541): 
,D/AndroidRuntime( 8265): 
D/AndroidRuntime( 8265): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8265): CheckJNI is OFF
,D/AndroidRuntime( 8265): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10455 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 6541:com.test.thalitest/u0a455 (adj 9): stop com.test.thalitest
,W/PackageSettings(  885): Skipping PackageSetting{31061535 com.example.hello/10440} due to missing metadata
,I/WindowState(  885): WIN DEATH: Window{375ddf98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  885): Client connection lost with reason: 4
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{16b84a76 u0 com.test.thalitest/.MainActivity t6}
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10455 user=0: pkg removed
,I/art     ( 3057): Explicit concurrent mark sweep GC freed 9503(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 7MB/12MB, paused 1.002ms total 39.177ms
,W/ActivityManager(  885): Spurious death for ProcessRecord{348d20bd 6541:com.test.thalitest/u0a455}, curProc for 6541: null
,W/GeofencerStateMachine( 1744): Ignoring removeGeofence because network location is disabled.
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1421): resetDictionaries() : en_US
D/VoicemailCleanupService( 8122): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1421): run()
,I/art     ( 6280): Explicit concurrent mark sweep GC freed 16908(1009KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/17MB, paused 771us total 135.427ms
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8294 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/SQLiteConnectionPool( 6280): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 1573): Explicit concurrent mark sweep GC freed 4922(303KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 508us total 163.663ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 411us total 21.938ms
,I/art     (  885): Explicit concurrent mark sweep GC freed 21512(1370KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.726ms total 157.116ms
,I/art     (  885): WaitForGcToComplete blocked for 69.950ms for cause Explicit
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.586ms
,I/Decoder ( 1421): createOrResetDecoder
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.097ms
,W/asset   ( 8294): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8294): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8294): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8294): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ConfigService( 1744): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): run()
,I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8321 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  885): removeObsoleteFile: deleting file=6_task.xml
,I/ActivityManager(  885): Killing 8073:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  885): Explicit concurrent mark sweep GC freed 6034(330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.634ms total 215.114ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1421): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1421): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1421): run()
I/StatsUtilsManager( 1421): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1421): shouldRecordStats() = Too Soon
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8073/cgroup.procs: No such file or directory
,W/ContextImpl( 8321): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6280): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6280): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6280): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6280): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 6280): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6280): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1744): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1744): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Launcher( 1573): Deferring update until onResume
,D/AndroidRuntime( 8265): Shutting down VM
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8343 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/LocationSettingsChecker( 6280): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 6280): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6280): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6280): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6280): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 6280): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 6280): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6280): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6280): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6280): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6280): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6280): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6280): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6280): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 6280): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 6280): Using Auth Proxy for data requests.
,I/GMPM-SVC( 6280): App measurement is starting up, version: 8489
I/GMPM-SVC( 6280): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b2b439e new=com.google.android.velvet.VelvetApplication@3b2b439e
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8368 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 6280): doRemovePackageData com.test.thalitest
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8399 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 8343): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/ConnectivityService(  885): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6280): CM callback handler got msg 524290
,E/Icing   ( 6280): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 6280): Writing status failed
,I/ActivityManager(  885): Killing 8173:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/Icing   ( 6280): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteLog( 8343): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
