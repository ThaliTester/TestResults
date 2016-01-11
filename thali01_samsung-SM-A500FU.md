#### Test 55634150e857e16_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/WebViewFactory( 2227): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/LibraryLoader( 2227): Time to load native libraries: 9 ms (timestamps 7663-7672)
I/LibraryLoader( 2227): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2227): Binding Chromium to main looper Looper (main, tid 1) {13a29c81}
I/LibraryLoader( 2227): Expected native library version number "",actual native library version number ""
I/chromium( 2227): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2227): Initializing chromium process, singleProcess=true
W/art     ( 2227): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2227): ApplicationContext is null in ApplicationStatus
D/WifiP2pService( 1017): InactiveState{ what=143375 }
E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 1017): VerifyingLinkState enter
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1017): Adding iface wlan0 to network 502
D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/chromium( 2227): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
E/USB_UICC(  295): Timeout! No signal received. Retry num = 21
D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 502
D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1017): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
D/ConnectivityService( 1017):    accepting network in place of null
D/ConnectivityService( 1017): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1459): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 1017): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1017): (HTTPLog)-Static: isShipBuild true
I/System.out( 1017): (HTTPLog)-Thread-135-448314822: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): forceRefresh() from cache miss
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1180): EthernetConnected: false
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
V/NetworkStats( 1017): performPollLocked() took 9ms
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/chromium( 2227): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2227): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 2227): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
I/Adreno-EGL( 2227): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2227): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2227): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2227): Local Branch: 
I/Adreno-EGL( 2227): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2227): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2227):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/NtpTrustedTime( 1017): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1452528582956 mCachedNtpElapsedRealtime : 28013 mCachedNtpCertainty : 35
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 16:09:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452528582943], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452528582895]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1180): EthernetConnected: false
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/AudioManagerAndroid( 2227): Requires BLUETOOTH permission
I/NSApplication( 2227): Starting up...
D/SettingsProvider( 1017): name = vibrate_in_silent
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/ResourcesManager( 1459): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/CscReceiver( 1459): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1459): Recieve Sim State Changed : ABSENT
I/splitIntent( 1017): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1017): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1459, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/WifiApBroadcastReceiver( 1318): onReceive: action android.intent.action.SIM_STATE_CHANGED
E/Zygote  ( 2315): MountEmulatedStorage()
E/Zygote  ( 2315): v2
I/libpersona( 2315): KNOX_SDCARD checking this for 1000
I/libpersona( 2315): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2325): MountEmulatedStorage()
I/libpersona( 2325): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2325): v2
I/libpersona( 2325): KNOX_SDCARD not a persona
I/SELinux ( 2325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/SELinux ( 2325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
D/BootupListener( 1459): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
D/PhoneUtilsCommon( 1459): isSupportVoLTE is false.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/TimaKeyStoreProvider( 2315): TimaSignature is unavailable
D/ActivityThread( 2315): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 2325): TimaSignature is unavailable
D/ActivityThread( 2325): Added TimaKeyStore provider
E/Zygote  ( 2342): MountEmulatedStorage()
E/Zygote  ( 2342): v2
I/libpersona( 2342): KNOX_SDCARD checking this for 10046
I/libpersona( 2342): KNOX_SDCARD not a persona
I/SELinux ( 2342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2342 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 2342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/SELinux ( 2342): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AlarmManagerService( 1017): Setting time of day to sec=1452528583
D/AlarmManagerService( 1017): Trying to open a file
D/AlarmManagerService( 1017): File Open Success
D/AlarmManagerService( 1017): File Close Success
I/AlarmManagerService( 1017): DRM_TIME_PATH CHMOD 666 for resetState done 
W/AlarmManagerService( 1017): Unable to set rtc to 1452528583: Invalid argument
V/AlarmManager( 1017): waitForAlarm result :65536
V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=28436 batch.start=45061
D/OTPFW   ( 1017): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1452528583377
D/WifiStateMachine( 1017): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
I/DowntimeConditions( 1017): android.intent.action.TIME_SET ignored because schedule turned off.
D/TimaKeyStoreProvider( 2342): TimaSignature is unavailable
D/ActivityThread( 2342): Added TimaKeyStore provider
D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/accuweather( 1727): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_SET
D/accuweather( 1727): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/SecKeyguardClockView( 1180): HomeTimezone(): 1
D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_SET
D/SettingsProvider( 1017): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/KeyguardEffectViewUtil( 1180): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 1180): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1180): update
D/KeyguardEffectViewUtil( 1180): getCurrentWallpaper() mWallpaperPath :null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2342): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2342): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2342): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2342): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2342): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/StatusChecker( 2315): onReceive : android.intent.action.SIM_STATE_CHANGED
I/StatusChecker( 2315): onReceive : net.mt.init : 
D/StatusChecker( 2315): onReceive : preference initializing
E/Zygote  ( 2367): MountEmulatedStorage()
E/Zygote  ( 2367): v2
I/libpersona( 2367): KNOX_SDCARD checking this for 1000
I/libpersona( 2367): KNOX_SDCARD not a persona
I/SELinux ( 2367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KeyguardEffectViewUtil( 1180): set current wallpaper info
I/SELinux ( 2367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2367 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1017): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/SettingsProvider( 1017): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/SettingsProvider( 1017): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/Zygote  ( 2380): MountEmulatedStorage()
I/libpersona( 2380): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2380): v2
I/libpersona( 2380): KNOX_SDCARD not a persona
I/SELinux ( 2380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 2367): TimaSignature is unavailable
E/SELinux ( 2380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/GpsLocationProvider( 1017): No APN found to select.
D/ActivityThread( 2367): Added TimaKeyStore provider
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/accuweather( 1727): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1727): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1727): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1727): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1727): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
E/LocSvc_eng( 1017): E/void loc_eng_agps_ril_update_network_availability(loc_eng_data_s_type&, int, const char*): log_eng state error: instance not initialized
E/accuweather( 1727): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 09
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
D/TimaKeyStoreProvider( 2380): TimaSignature is unavailable
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 2380): Added TimaKeyStore provider
E/Zygote  ( 2397): MountEmulatedStorage()
I/libpersona( 2397): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2397): v2
I/libpersona( 2397): KNOX_SDCARD not a persona
I/SELinux ( 2397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TEST    ( 1180): run!!!
D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
E/SELinux ( 2397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  302): Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 659us total 29.208ms
I/ActivityManager( 1017): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2397 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/GeometricMosaic_Renderer( 1180): setBackgroundBitmap
D/AndroidRuntime( 2361): 
D/AndroidRuntime( 2361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 668us total 17.712ms
D/AndroidRuntime( 2361): CheckJNI is OFF
D/TimaKeyStoreProvider( 2397): TimaSignature is unavailable
D/AndroidRuntime( 2361): readGMSProperty: start
D/AndroidRuntime( 2361): readGMSProperty: already setted!!
D/AndroidRuntime( 2361): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2361): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2361): readGMSProperty: end
D/AndroidRuntime( 2361): addProductProperty: start
D/ActivityThread( 2397): Added TimaKeyStore provider
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 18.999ms
I/Omc:Receiver( 2380): onReceive : android.intent.action.SIM_STATE_CHANGED
D/Mms/MmsApp( 2342): [start]    onCreate() consume time = 0.0
I/Omc:OmcData( 2380): omc.xml not exist
I/Omc:Receiver( 2380): OM Customize disabled
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2419 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 2419): MountEmulatedStorage()
E/Zygote  ( 2419): v2
I/libpersona( 2419): KNOX_SDCARD checking this for 10131
I/libpersona( 2419): KNOX_SDCARD not a persona
I/SELinux ( 2419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2419): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/USB_UICC(  295): Timeout! No signal received. Retry num = 22
D/TimaKeyStoreProvider( 2419): TimaSignature is unavailable
D/ActivityThread( 2419): Added TimaKeyStore provider
E/SMD     (  287): DCD OFF
W/ResourcesManager( 2419): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2419): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2419): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2419): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/AffinityControl( 2361): AffinityControl: registerfunction enter
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/AndroidRuntime( 2361): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/art     ( 2342): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 115.075ms
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1017): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1017): Set to : 0
I/WifiNative-HAL( 1017): startHal
E/wifi    ( 1017): getStaticLongField sWifiHalHandle 0x9c9e98bc
I/WifiNative-HAL( 1017): Could not start hal
D/Launcher.HomeView( 1481): onPause
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1481
D/AndroidRuntime( 2361): Shutting down VM
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2437): MountEmulatedStorage()
E/Zygote  ( 2437): v2
I/libpersona( 2437): KNOX_SDCARD checking this for 10177
I/libpersona( 2437): KNOX_SDCARD not a persona
I/SELinux ( 2437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2437 uid=10177 gids={50177, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2437): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1481): updateVisibility : ActivityRecord{17f7f976 token=android.os.BinderProxy@c72a47e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 2437): TimaSignature is unavailable
D/ActivityThread( 2437): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Mms/ArtClassLoader( 2342): init before art
D/Launcher.HomeView( 1481): onStop
V/ActivityThread( 1481): updateVisibility : ActivityRecord{17f7f976 token=android.os.BinderProxy@c72a47e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1481): onTrimMemory. Level: 20
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/Mms/TelephonyPermission( 2342): start operation mode monitor
D/SBrowserFeatureFlag( 2419): initialized in static block : loadCscFeatureValue() succeed! 
W/ResourcesManager( 2342): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2342): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2342): isDefault true
D/Mms/MmsApp( 2342): onCreate() com.android.mms
D/ManifestProvider( 2419): onCreate()
I/WebViewFactory( 2437): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
E/OperatorBookmarksSIMReceiver( 2419): onReceive runs..android.intent.action.SIM_STATE_CHANGED
I/LibraryLoader( 2437): Time to load native libraries: 2 ms (timestamps 9123-9125)
I/LibraryLoader( 2437): Expected native library version number "",actual native library version number ""
W/art     ( 2361): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Mms/MmsApp( 2342): [start]    initCountryIso consume time = 435.001041
V/WebViewChromiumFactoryProvider( 2437): Binding Chromium to main looper Looper (main, tid 1) {2ac6af89}
I/LibraryLoader( 2437): Expected native library version number "",actual native library version number ""
I/chromium( 2437): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
D/CountryDetector( 1017): The first listener is added
,D/Mms/MmsApp( 2342): [end]    initCountryIso consume time = 14.723646
,D/Mms/MmsConfig( 2342): [start]    MmsConfig.init() consume time = 0.671771
,D/Mms/MmsConfig( 2342): before partial update
,D/Mms/MmsConfig( 2342): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 2342): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 2342): isAuth is false
,D/Mms/MmsConfig( 2342): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/BrowserStartupController( 2437): Initializing chromium process, singleProcess=true
,W/art     ( 2437): Attempt to remove local handle scope entry from IRT, ignoring
,D/TP/MmsSmsProvider( 1459): query,matched:2117, calling pid = 2342
E/SysUtils( 2437): ApplicationContext is null in ApplicationStatus
,D/TP/MmsSmsProvider( 1459): match 2117:Elapsed time : 2.746 ms
,D/EasySignUpManager_1.0.1( 2342): isAuth is false
D/EasySignUpManager_1.0.1( 2342): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 2342): mps_code.dat does not exist
E/CscParser( 2342): customer_path =/system/csc/customer.xml
E/CscParser( 2342): fileName + /system/csc/customer.xml
,E/CscParser( 2342): mps_code.dat does not exist
E/CscParser( 2342): customer_path =/system/csc/customer.xml
E/CscParser( 2342): fileName + /system/csc/customer.xml
,W/chromium( 2437): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2437): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2437): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 2437): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2437): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2437): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2437): Local Branch: 
I/Adreno-EGL( 2437): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2437): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2437):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/CscParser( 2342): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 2342):  enable multiwindow = true
,E/Mms/MessageUtils( 2342): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2342): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 2342): [end]    init() consume time = 89.569948
,D/Mms/Contact( 2342): [start]    init() consume time = 3.037604
,D/Mms/Contact( 2342): [end]    init consume time = 17.598021
,D/TP/MmsSmsProvider( 1459): query,matched:13, calling pid = 2342
,D/TP/MmsSmsProvider( 1459): match 13:Elapsed time : 1.170 ms
,D/Mms/DraftCache( 2342): [start]    rebuildCache consume time = 7.66026
,D/TP/MmsSmsProvider( 1459): query,matched:12, calling pid = 2342
D/TP/MmsSmsProvider( 1459): match 12:Elapsed time : 2.736 ms
D/BluetoothAdapter( 2437): 143258266: getState() :  mService = null. Returning STATE_OFF
D/Mms/DraftCache( 2342): [end]    rebuildCache consume time = 21.897344
,D/Mms/MethodReflector( 2342): getSubId is called
,D/Mms/TelephonyUtils( 2342): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 2342): getTelephonyProperty is called
D/Mms/DownloadManager( 2342): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2342): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2342): auto download without roaming -> true
D/Mms/DownloadManager( 2342): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 2342): getSubId is called
,D/Mms/MethodReflector( 2342): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2342): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2342): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2342): getTelephonyProperty is called
D/Mms/DownloadManager( 2342): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2342): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2342): auto download without roaming -> true
D/Mms/DownloadManager( 2342): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2342): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2342): mAutoDownload ------> true
,W/chromium( 2437): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/ComposerPerformance( 2342): 1452528584376 ms / [DONE] Composer constructor
,E/CII     ( 2342): CommonIMSInterface: VoLTE CSC feature disabled.
,D/Mms/ArtClassLoader( 2342): init [DONE] art
,D/Mms/Conversation( 2342): [start]    init() consume time = 114.153594
,I/Mms/ReservationManager( 2342): ReservationManager()
I/Mms/ReservationManager( 2342): resetAfterConnected()
,D/TP/MmsSmsDatabaseHelper( 1459): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 1459): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1459): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1459): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1459): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1459): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1459): query,matched:7, calling pid = 2342
,I/SurfaceFlinger(  257): id=6 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/8)
,D/TP/MmsSmsProvider( 1459): match 7:Elapsed time : 4.182 ms
,D/TP/MmsSmsProvider( 1459): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1459): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1459): sUpgradeVersion = 0, db.getVersion() = 81
,I/Mms/ReservationManager( 2342): getReservedSendMessageCount(): retMessageCount=0
,E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/MmsApp( 2342): [end]    onCreate() consume time = 33.624062
,D/Mms/SmsReceiver( 2342): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
,D/TP/MmsSmsProvider( 1459): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
,D/Mms/Conversation( 2342): [end]    init consume time = 4.105573
,D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/art     ( 2437): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/Mms/DownloadManager( 2342): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 2342): roaming ------> false, mSimSlot = 0
I/splitIntent( 1017): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/Mms/MethodReflector( 2342): getSubId is called
D/Mms/TelephonyUtils( 2342): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 2342): getTelephonyProperty is called
D/Mms/DownloadManager( 2342): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2342): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2342): auto download without roaming -> true
D/Mms/DownloadManager( 2342): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/BootupListener( 1459): intent.getAction() = android.intent.action.SERVICE_STATE
,D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1459): isSupportVoLTE is false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/Mms/DownloadManager( 2342): mAutoDownload ------> true
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
,D/StatusChecker( 2315): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2315): onReceive : net.mt.init : DONE
,D/Mms/MessagingNotification( 2342): [start]    init() consume time = 26.749427
,D/StatusChecker( 2315): Service state changed : 3 mSub-1
,D/Mms/MessagingNotification( 2342): [end]    init consume time = 5.007865
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AwContents( 2437): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/Synchronizer( 2342): [start]    doSync consume time = 20.103229
,D/TP/MmsSmsProvider( 1459): query,matched:0, calling pid = 2342
D/Mms/SpamFilter( 2342): [start]    SpamFilter fill() begin consume time = 1.994583
,V/TP/MmsSmsProvider( 1459): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1459): match 0:Elapsed time : 1.781 ms
D/PhoneWindow( 2437): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2437): *FMB* installDecor flags : 8456448
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/SystemWebViewEngine( 2437): CordovaWebView is running on device made by: samsung
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1459): update, matched:300, calling pid = 2342
,D/Mms/SmsReceiverService( 2342): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsProvider( 1459): syncDBData start
,D/TP/MmsSmsProvider( 1459): query,matched:400, calling pid = 2342
,V/TP/MmsSmsProvider( 1459): syncDBData sms end
,V/TP/MmsSmsProvider( 1459): syncDBData mms end
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
V/TP/MmsSmsProvider( 1459): syncDBData end
D/Mms/TelephonyPermission( 2342): isDefault true
D/Mms/SmsReceiverService( 2342): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2342): handleSIMStatus()
D/Mms/SmsReceiverService( 2342): handleSIMStatus(): SIM_STATUS = ABSENT
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/art     ( 2437): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2437): Attempt to remove local handle scope entry from IRT, ignoring
,D/Mms/Synchronizer( 2342): [end]    doSync consume time = 25.94125
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/SpamFilter( 2342): [end]    SpamFilter fill() finished consume time = 24.42099
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 2342): checkBadgeCount unreadCount=0 badgeCount=0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/OpenGLRenderer( 2437): Render dirty regions requested: true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/SmsProvider( 1459): query,matched:26, calling pid = 2342
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/TP/SmsProvider( 1459): match 26:Elapsed time : 2.430 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneWindow( 2437): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2437): *FMB* isFloatingMenuEnabled return false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,E/Zygote  ( 2490): MountEmulatedStorage(),
E/Zygote  ( 2490): v2
I/libpersona( 2490): KNOX_SDCARD checking this for 10020
I/libpersona( 2490): KNOX_SDCARD not a persona
,I/SELinux ( 2490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2490 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a,
I/SELinux ( 2490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2490): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1459): query,matched:6, calling pid = 2342
,D/TP/MmsSmsProvider( 1459): match 6:Elapsed time : 3.061 ms
D/InputDispatcher( 1017): Focus entered window: 2437
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2437): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2437): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2437): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2437): Enabling debug mode 0
,D/TimaKeyStoreProvider( 2490): TimaSignature is unavailable
D/ActivityThread( 2490): Added TimaKeyStore provider
,W/ResourcesManager( 2490): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2490): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2507): MountEmulatedStorage()
I/libpersona( 2507): KNOX_SDCARD checking this for 10025
E/Zygote  ( 2507): v2
I/libpersona( 2507): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2507 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
,I/SELinux ( 2507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 2507): TimaSignature is unavailable
,D/ActivityThread( 2507): Added TimaKeyStore provider
,W/ResourcesManager( 2507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 23
,I/ActivityManager( 1017): Displayed Component not be shown by security: +882ms
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{36122476 u0 com.example.hello/.MainActivity t2} time:29828
,I/Timeline( 2437): Timeline: Activity_idle id: android.os.BinderProxy@2924afec time:29834
,I/SamsungIME( 1815): getCurrentCandidateView
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/OMACP   ( 2507): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 2342): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 2507): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/SamsungIME( 1815): Dismiss ExpandCandiate
,D/EasySignUpManager_1.15.0305( 2490): serviceId : 0, features : -1
,I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2530): MountEmulatedStorage()
E/Zygote  ( 2530): v2
I/libpersona( 2530): KNOX_SDCARD checking this for 10044
I/libpersona( 2530): KNOX_SDCARD not a persona
,I/SELinux ( 2530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2530 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,D/SecContentProvider2( 1017): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): isCopyContactToSimAllowed = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2530): TimaSignature is unavailable
,D/ActivityThread( 2530): Added TimaKeyStore provider,
,W/BindingManager( 2437): Cannot call determinedVisibility() - never saw a connection for the pid: 2437
E/Zygote  ( 2544): MountEmulatedStorage(),
I/libpersona( 2544): KNOX_SDCARD checking this for 10088
E/Zygote  ( 2544): v2
,I/libpersona( 2544): KNOX_SDCARD not a persona
I/SELinux ( 2544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2544): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2544 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,I/chromium( 2437): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2544): TimaSignature is unavailable
,D/ActivityThread( 2544): Added TimaKeyStore provider
,E/Zygote  ( 2562): MountEmulatedStorage()
E/Zygote  ( 2562): v2
I/libpersona( 2562): KNOX_SDCARD checking this for 10142
I/libpersona( 2562): KNOX_SDCARD not a persona
,I/SELinux ( 2562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2562 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2562): TimaSignature is unavailable
,D/ActivityThread( 2562): Added TimaKeyStore provider
,D/JsMessageQueue( 2437): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1815): getDebugLevel  : 0x4f4c
,E/AndroidProtocolHandler( 2437): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 48008(2MB) AllocSpace objects, 5(194KB) LOS objects, 33% free, 25MB/37MB, paused 2.291ms total 165.585ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,I/SamsungIME( 1815): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1815): KeybaordView init() : load resources
W/ResourcesManager( 2530): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2530): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2530): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2530): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2530): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2530): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2530): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 2544): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2579): MountEmulatedStorage()
E/Zygote  ( 2579): v2
I/libpersona( 2579): KNOX_SDCARD checking this for 10054
I/libpersona( 2579): KNOX_SDCARD not a persona
,I/SELinux ( 2579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2579): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2579 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
,V/TaskCloserActivity( 2562): TaskCloserActivity enter()
,D/TimaKeyStoreProvider( 2579): TimaSignature is unavailable
,D/ActivityThread( 2579): Added TimaKeyStore provider
,V/TaskCloserActivity( 2562): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ResourcesManager( 2579): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,I/dhcpcd  ( 2181): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 2181): wlan0: sendmsg: Cannot assign requested address
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/SamsungIME( 1815): getCurrentKeyboard
I/SamsungIME( 1815): getTextKeyboard
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2595): MountEmulatedStorage()
I/libpersona( 2595): KNOX_SDCARD checking this for 10139
E/Zygote  ( 2595): v2
I/libpersona( 2595): KNOX_SDCARD not a persona
,I/SELinux ( 2595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SamsungIME( 1815): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/SELinux ( 2595): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2595 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,D/jxcore_app_log( 2437): JniHelper::setJavaVM(0xb7e34450), pthread_self() = -1204252520
,D/JX-Cordova( 2437): jxcore cordova android initializing
E/SELinux ( 2595): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2595): TimaSignature is unavailable
,D/ActivityThread( 2595): Added TimaKeyStore provider
,D/Recents_RecreateReceiver( 2579): onReceive by home
,W/ResourcesManager( 2595): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2595): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2595): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2595): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2595): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/jxcore-log( 2437): Initializing JXcore engine
W/jxcore-log( 2437): JXcore engine is ready
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
W/jxcore-log( 2437): Starting JXcore engine
,D/SecContentProvider2( 1017): mCursor = null
,W/art     ( 2490): Verification of void com.android.contacts.activities.PeopleActivity.Y() took 127.978ms
,E/audit   ( 1930): type=1400 msg=audit(1452528585.589:205): avc:  denied  { ioctl } for  pid=2437 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1930):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1930): type=1300 msg=audit(1452528585.589:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=bed06d58 items=0 ppid=302 ppcomm=main pid=2437 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1930): type=1320 msg=audit(1452528585.589:205): 
,W/jxcore-log( 2437): Platform android
W/jxcore-log( 2437): 
,W/jxcore-log( 2437): Process ARCH arm
W/jxcore-log( 2437): 
W/art     ( 2490): Verification of void com.android.contacts.common.list.l.P() took 110.746ms
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 24
,I/jxcore-log( 2437): JXcore Cordova bridge is ready!
I/jxcore-log( 2437): 
,W/jxcore-log( 2437): JXcore engine is started
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {134f761a}
,D/NearbySource( 2530): Nearby Source Create!
,D/NearbyContext( 2530): Nearby Context Create!
,E/jxcore-log( 2437): >> samsung-SM-A500FU
E/jxcore-log( 2437): 
,I/jxcore-log( 2437): Total memory 1983791104
I/jxcore-log( 2437): 
,I/jxcore-log( 2437): Free memory 403574784
I/jxcore-log( 2437): 
I/jxcore-log( 2437): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2437): 
I/jxcore-log( 2437): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2437): 
,I/jxcore-log( 2437): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log( 2437): 
,I/jxcore-log( 2437): Size 720 1280
I/jxcore-log( 2437): 
,I/jxcore-log( 2437): Screen Brightness 5
I/jxcore-log( 2437): 
,E/jxcore-log( 2437): Dummy Error Log.
E/jxcore-log( 2437): 
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2530): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2530): Samsung link source created
,D/ContactProvider( 2530): getAllContactInfoList Start
,D/AbsListView( 2490): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SQLiteLog( 1227): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2530): Receive : home resume
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 2342): ui event
,I/splitIntent( 1017): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1727): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/ContactProvider( 2530): getAllContactInfoList End
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,I/syncContacts( 2530): thread: 253, sync time = 87
,D/accuweather( 1727): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1727): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1727): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1727): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
D/accuweather( 1727): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1727): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1727): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
D/accuweather( 1727): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1727): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 09
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): start check captive portal 
E/accuweather( 1727): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1727): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1727): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1727): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1727): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1727): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1727): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SamsungIME( 1815): [SwiftkeyWrapper] currentLangauge : 1701729619,
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1304): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1304): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SIP     ( 1459): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1459): fail readDirectory() errno=2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 2342):  start initViewCache mms
I/jxcore-log( 2437): getBuffer is called!!!!
I/jxcore-log( 2437): 
,D/Mms/ComposeMessageFragment( 2342): [start]    fillCache consume time = 1893.702239
D/Mms/ComposeMessageFragment( 2342): fillCache, easy = false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1846): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1304): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1304): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/AbsListView( 2342): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 2342): [end]    fillCache consume time = 123.819635
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:750 [0:0] Cncl30MinRftAl
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:1056 [0:0] == cityListItem Size : 0
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:904 [0:0] MR pcknme : Manual systemui
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:257 [0:0] == rCL 1452528586587
,E/SQLiteLog( 1846): (283) recovered 48 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1304): [MSC_Daemon]>>> RM:273 [0:0] EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
,D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
,D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:1895 [0:0] MCL getLLoc@
D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
,D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr!!
,D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:1956 [0:0] PrvdrErr getPerformLoc:true
D/daemonapp( 1304): [MSC_Daemon]>>> WMCL:1958 [0:0] MCL pfL set:f
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1452528586634
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1452550186628
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1304): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1452550140000
,D/daemonapp( 1304): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1452550140000
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1452550140000
,D/daemonapp( 1304): [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:1314 [0:0] CL@AtRfr = 3
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:1321 [0:0]  AR_lasttime: 1452550140000
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1615 [0:0] util getnext by widget 1452550140000
D/daemonapp( 1304): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1452550140000
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:1332 [0:0] NextTime       :1452550140000
D/daemonapp( 1304): [MSC_Daemon]>>> AWCLRH:242 [0:0] rLH /on rciclf
D/daemonapp( 1304): [MSC_Daemon]>>> RM:1480 [0:0]  retryCityIdCurrentlocationfail getRefreshType : 3
D/daemonapp( 1304): [MSC_Daemon]>>> RM:1491 [0:0] send broad cast error to clock
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2628): MountEmulatedStorage()
E/Zygote  ( 2628): v2
I/libpersona( 2628): KNOX_SDCARD checking this for 1000
I/libpersona( 2628): KNOX_SDCARD not a persona
,I/SELinux ( 2628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2628 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 2628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2628): TimaSignature is unavailable
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/ActivityThread( 2628): Added TimaKeyStore provider
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,D/Mms/BubbleViewCache( 2342): fillCache bubble = 1
,E/daemonapp( 1304): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
D/AdaptiveEventManager( 1180): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,D/AdaptiveEventManager( 1180): currentCityId is null
D/AdaptiveEventManager( 1180): NetWork disabled : Don't refresh weather info : 201
D/AdaptiveEventManager( 1180): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1180): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): mWeatherInfo is not reliable
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 25
E/daemonapp( 1304): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
,E/Zygote  ( 2645): MountEmulatedStorage()
I/libpersona( 2645): KNOX_SDCARD checking this for 10135
E/Zygote  ( 2645): v2
I/libpersona( 2645): KNOX_SDCARD not a persona
,I/SELinux ( 2645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2645 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
D/SecurityLogAgent( 2628):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/daemonapp( 1304): [MSC_Daemon]>>> WDBH:4086 [0:0] ud SLS false
,D/SecurityLogAgent( 2628):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2628):  SeDenialReceiver : Start file Zipping Service 
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:1344 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
D/daemonapp( 1304): [MSC_Daemon]>>> RM:1349 [0:0] =======RefreshType:1 End RetThd Current===========
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
D/daemonapp( 1304): [MSC_Daemon]>>> RM:1236 [0:0] resetRefreshThread : 0
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/daemonapp( 1304): [MSC_Daemon]>>> RM:1441 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
D/SecurityLogAgent( 2628): FileZippingService : onHandleIntent 
D/daemonapp( 1304): [MSC_Daemon]>>> RM:1353 [0:0] send broad cast to clock Cur
D/SecurityLogAgent( 2628): FileZippingService : file path =  /data/misc/audit/audit.old
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/art     (  302): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.170ms total 32.894ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2628): FileZippingService : onPremise disabled. Zipping..  
D/TimaKeyStoreProvider( 2645): TimaSignature is unavailable
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityThread( 2645): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.100ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : Not empty 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 16.933ms
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator File existence : true audit.old file size 643
W/ResourcesManager( 2645): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2645): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2645): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2628): FileZippingService : completed task. Returning wakelock . 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2663): MountEmulatedStorage()
E/Zygote  ( 2663): v2
I/libpersona( 2663): KNOX_SDCARD checking this for 1000
I/libpersona( 2663): KNOX_SDCARD not a persona
,I/SELinux ( 2663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2663 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 2663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2663): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Scheduler( 1846): Use legacy PeriodicScheduler
,D/TimaKeyStoreProvider( 2663): TimaSignature is unavailable
,D/ActivityThread( 2663): Added TimaKeyStore provider
,W/InstanceID/Rpc( 1846): Found 10012
,W/ContextImpl( 2663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2682): MountEmulatedStorage()
,E/Zygote  ( 2682): v2
I/libpersona( 2682): KNOX_SDCARD checking this for 1000
I/libpersona( 2682): KNOX_SDCARD not a persona
I/SELinux ( 2682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2682): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2682): TimaSignature is unavailable
,D/ActivityThread( 2682): Added TimaKeyStore provider
,W/ResourcesManager( 2682): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2682): [FactoryTestBroadcastReceiver$onReceive](2682) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2682): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2682): [XMLDataStorage$parseXML](2682) is Live Demo : false
,D/FactoryTestApp( 2682): [XMLDataStorage$parseXML](2682) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2682): [XMLDataStorage$parseXML](2682) deviceXML=a5ulte.dat
D/FactoryTestApp( 2682): [XMLDataStorage$parseXML](2682) nameXML=a5ultexx.dat
,D/FactoryTestApp( 2682): [XMLDataStorage$parseAsset](2682) parseAsset Is Started
,I/FactoryTestApp( 2682): [XMLDataStorage$parseAsset](2682) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2682): [XMLDataStorage$parseAsset](2682) Decode base file: factory.dat
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FACTORY_TEST_APP
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FAILHIST_VERSION
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=MODEL_NAME
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=MODEL_NUMBER
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=CHIPSET_NAME
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=DEVICE_TYPE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=BATT_TYPE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PANEL_TYPE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SPEAKER_COUNT
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=MIC_COUNT
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_LTE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_RCV
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_EPEN
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=NEED_CAMDRIVER_OPEN
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HW_VER_EFS
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_AP_EX_THERM_ADC
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FONT_SIZE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=RAM_SIZE_IF
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=MULTI_TSK_THD
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=NEED_LPA_MODE_SET
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_GRAPHIC_ACCLETOR
D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_POWER
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_HOME
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_BACK
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_GEOMAGNETIC_ALPS_CAL,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SENSOR_TEST_ACC_BIT,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=G_VECTOR_SUM_ACC_BIT,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_VIBETONZ_UNSUPPORTED,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=AT_GPSSTEST,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=AT_BATTEST_RESET_WHEN_READ,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SUPPORT_CHARGE_COUNT,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HALL_IC_TEST
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_NEW_TSP_SELFTEST_SYNAPTICS,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=READ_TARGET_GEOMAGNETIC,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=BATTERY_VF_OCV
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=SEC_EXT_THERMISTER_TEMP
I/GAV4    ( 2227): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_COMMAND_CMD
,I/GAv4-SVC( 2067): Google Analytics 8.4.89 is starting up.
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=LPA_MODE_SET
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2682): [XMLDataStorage$redefinitionById](2682) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2682): [XMLDataStorage$parseAsset](2682) SemiFunctionMenu
,D/FactoryTestApp( 2682): [XMLDataStorage$parseAsset](2682) parseAsset Is Completed
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2682): [ModuleCommon$ModuleCommon](2682) Create ModuleCommon
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2682): [Support$Kernel.read](2682) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2682): [ModuleCommon$readFactoryMode](2682) mode: ON
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2682): [FactoryTestBroadcastReceiver$onReceive](2682) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2682): [Support$Values.getBoolean](2682) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 2682): [Support$Properties.get](2682) property=ro.factory.factory_binary
D/FactoryTestApp( 2682): [FactoryTestBroadcastReceiver$onReceive](2682) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2682): [ModuleCommon$getFtClientEnableState](2682) result : false
I/FactoryTestApp( 2682): [ModuleCommon$connectedJIG](2682) ...
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2682): [ModuleCommon$connectedJIG](2682) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2682): [Support$Kernel.read](2682) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 2682): [ModuleCommon$connectedJIG](2682) value = 1f, JIG_ON = 1C
,D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2682): [ModuleCommon$isConnectionModeNone](2682) mConnectionMode = gsm
I/FactoryTestApp( 2682): [ModuleCommon$isRunningFtClient](2682) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2682): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2682) start DummyFtClient service for APO
,W/ContextImpl( 2682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2682): User mode
,I/FactoryTestApp( 2682): [ModuleCommon$disableFtClient](2682) ...
,D/FactoryTestApp( 2682): [DummyFtClient$onCreate](2682) Create DummyFtClient service
,I/FactoryTestApp( 2682): [XMLDataStorage$parsingXML](2682) FtClient => data parsing was completed.
,D/FactoryTestApp( 2682): [DummyFtClient$onReceive](2682) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.,
D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2682): [ModuleCommon$isConnectionModeNone](2682) mConnectionMode = gsm
,D/FactoryTestApp( 2682): [Support$Values.getBoolean](2682) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2682): [DummyFtClient$onStartCommand](2682) ...
,E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2706): MountEmulatedStorage()
,E/Zygote  ( 2706): v2
I/libpersona( 2706): KNOX_SDCARD checking this for 1002
I/libpersona( 2706): KNOX_SDCARD not a persona
,I/SELinux ( 2706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2706 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/WifiService( 1017): android.intent.action.BOOT_COMPLETED
I/SELinux ( 2706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/UsbDeviceManager( 1017): boot completed
D/UsbDeviceManager( 1017): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1017): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
D/UsbDeviceManager( 1017): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2722): MountEmulatedStorage()
E/Zygote  ( 2722): v2
I/libpersona( 2722): KNOX_SDCARD checking this for 1000
I/libpersona( 2722): KNOX_SDCARD not a persona
I/SELinux ( 2722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 2706): TimaSignature is unavailable
,I/SELinux ( 2722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 2706): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KeyguardEffectViewUtil( 1180): set resource id
,D/UsbDeviceManager( 1017): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
D/SettingsProvider( 1017): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 2706): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 2706): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/PalmMotion( 1017): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1017): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1017): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1017): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaKeyStoreProvider( 2722): TimaSignature is unavailable
,D/ActivityThread( 2722): Added TimaKeyStore provider
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NfcService( 1446): call the applyRouting
,D/SamsungIME( 1815): showDlgMsgBox : false true true
,I/RecoverySystem( 1017): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1017): No recovery log file
,I/BluetoothA2dpSinkServiceJni( 2706): register_com_android_bluetooth_a2dp_sink
,D/ActivityManager( 1017): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/File    ( 2722): fail readDirectory() errno=2
,V/OtaStartupReceiver( 1459): onOtaspChanged: mOtaspMode=1
,D/Reset_Reason( 1017): resetString = NPON
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2748): MountEmulatedStorage()
I/libpersona( 2748): KNOX_SDCARD checking this for 1001
E/Zygote  ( 2748): v2
I/libpersona( 2748): KNOX_SDCARD not a persona
,I/SELinux ( 2748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/BootReceiver( 1017): Copying audit failures to DropBox
I/BootReceiver( 1017): Checking for fsck errors
,I/SELinux ( 2748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2748): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/ActivityManager( 1017): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2748 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 2748): TimaSignature is unavailable
,D/ActivityThread( 2748): Added TimaKeyStore provider
,D/BtSettings.ProfileConfig( 2706): Adding GattService
,D/BtSettings.ProfileConfig( 2706): Adding HeadsetService
,D/BtSettings.ProfileConfig( 2706): Adding A2dpService
,D/BtSettings.ProfileConfig( 2706): Adding HidService
D/BtSettings.ProfileConfig( 2706): Adding HealthService
D/BtSettings.ProfileConfig( 2706): Adding PanService
D/BtSettings.ProfileConfig( 2706): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 2706): Adding SapService
D/BtSettings.ProfileConfig( 2706): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 2706): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 2706): Adding SapClientService
D/BtSettings.ProfileConfig( 2706): Adding HidDevService
I/BtSettings.ProfileConfig( 2706): *********Initializing Bluetooth Profile Settings*******
D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 26
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 2748): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,E/ActivityThread( 2067): Failed to find provider info for com.android.contacts.metadata
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/ActivityManager( 1017): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/FactoryTestApp( 2682): [ProtectedFactoryTestBroadcastReceiver$onReceive](2682) onReceive action=com.samsung.intent.action.SECPHONE_READY
,I/FactoryTestApp( 2682): [ProtectedFactoryTestBroadcastReceiver$onReceive](2682) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2682): User mode
,D/Mms/NotificationReceiver( 2342): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,D/Mms/NotificationReceiver( 2342): handleBootCompleted()
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.broadcom.bt.service.sap.SapService,
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/Mms/RcsOwnCapsManager( 2342): queue Uri = content://im/queue-messages?box=pending
,D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/TP/ImProvider( 1459): im query match24
D/TP/ImProvider( 1459): URI_IM_QUEUED_MESSAGES
,D/TP/ImProvider( 1459): ftSesstionId must be a long.
D/TP/ImProvider( 1459): getQueuedImMessages
,D/TP/ImProvider( 1459): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 25160, reason: UserStart, SyncResult: databaseError: true stats []
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/SyncManager( 1017): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 63676, reason: UserStart
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/NotificationReceiver( 2342):  getPendingMessageIds: no pending messages.
,D/Mms/ActionsFactory( 2342): Call to GET_LAST_MESSAGES_SENT
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text,
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/art     ( 1017): Suspending all threads took: 7.365ms
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 38574(2029KB) AllocSpace objects, 8(1001KB) LOS objects, 33% free, 26MB/40MB, paused 10.581ms total 200.523ms
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 31510, tid: 31510, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b914bd48  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b914bd48  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 ba64e378  sl ba64e378  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr a0b0030c  pc a0affd98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859ec62bb0  d1  0000000000000000
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):       
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/BootReceiver( 1017): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/BluetoothAdapterState( 2706): make
D/SettingsProvider( 1017): name = db_smartlock_supported
,I/bluedroid( 2706): init
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 2016, tid: 2016, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b926a1f0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b926a1f0  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 baf12548  sl baf12548  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr a09c330c  pc a09c2d98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859e8579c0  d1  0000000000000000
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):     ,     be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):         
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
I/BluetoothAdapterState( 2706): Entering OffState
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/BootReceiver( 1017): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/bte_conf( 2706): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 8409, tid: 8409, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b9145f50  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b9145f50  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 bab49fd0  sl bab49fd0  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr 9fdfc30c  pc 9fdfbd98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859df5ebb0  d1  646f6d5f65646f6e
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000012
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):          be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):         
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
I/bte_conf( 2706): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2706): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2706): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/SensorService( 1017): [SO] 0.057 0.153 10.094
I/AccessibilityManagerService( 1017): setmDNIeNegative (false)
E/bt-btif ( 2706): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 2706): get_profile_interface socket
I/bluedroid( 2706): get_profile_interface map_client
D/BluetoothAdapterService( 2706): checkAddrForIOP: Loading from conf
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/GKI_LINUX( 2706): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 2706): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 2706): populateRssiValuesNative
I/bluedroid( 2706): getModelRssiValues
E/BluetoothServiceJni( 2706): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2706): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothA2dp( 2706): doBind(): CallingUid(myUserHandle) = 0
D/BluetoothAdapterProperties( 2706): Name is: A5-1
D/ActivityManager( 1017): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 10813, tid: 10813, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b92c7dd0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b92c7dd0  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 b9a6af30  sl b9a6af30  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr a0d6430c  pc a0d63d98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859ec579c0  d1  0000000000000000
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000012
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):          be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):       
D/CrashAnrDetector( 1017): processName:com.test.thalitest
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
D/SettingsProvider( 1017): name = bluetooth_name
I/bluedroid( 2706): config_hci_snoop_log
W/art     ( 2067): Suspending all threads took: 11.568ms
D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 10 receivers.
D/BluetoothManagerService( 1017): Ble is always on enable gatt
I/BluetoothManagerService( 1017): enableGattForLeMode, doBind called
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
I/BtGatt.JNI( 2706): classInitNative(L900): classInitNative: Success!
D/SecContentProvider( 1017): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/BluetoothAdapterState( 2706): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 2706): Setting state to 11
I/BluetoothAdapterState( 2706): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2706): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2706): updateAdapterState state is 11
,D/BluetoothAdapterService( 2706): Autoconnection is available 
D/BluetoothAdapterService( 2706): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 2706): getInstant: null
D/BluetoothSecureManager( 2706): calling getMethod for getService
D/BluetoothSecureManager( 2706): calling getService
,D/BluetoothSecureManager( 2706): getService return binder: android.os.BinderProxy@1ae90dfd
,D/BluetoothSecureManagerService( 1017): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1017): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 2706): isSecureModeOn:false
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 6058, tid: 6772, name: Thread-1061  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9c909ff0
D/CrashAnrDetector( 1017):     r0 710804a8  r1 735927c8  r2 12dd4780  r3 13533ec0
D/CrashAnrDetector( 1017):     r4 000000c2  r5 710804a8  r6 735927c8  r7 13533ec0
D/CrashAnrDetector( 1017):     r8 73592770  r9 ba677458  sl 12dd4780  fp 9ca0b8a8
D/CrashAnrDetector( 1017):     ip 9c909ff0  sp 9c90bff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1017):     d0  12dd4780735927c0  d1  007300200065003e
D/CrashAnrDetector( 1017):     d2  c0c0c0c0c0c0c053  d3  0102020202020213
D/CrashAnrDetector( 1017):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1017):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1017):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1017):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1017):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1017):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1017):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1017):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1017):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          9c90bf70  00000000  
D/CrashAnrDetector( 1017):          9c90bf74  00000000  
D/CrashAnrDetector( 1017):          9c90bf78  00000000  
D/CrashAnrDetector( 1017):          9c90bf7c  00000000  
D/CrashAnrDetector( 1017):          9c90bf80  00000000  
D/CrashAnrDetector( 1017):          9c90bf84  00000000  
D/CrashAnrDetector( 1017):          9c90bf88  00000000  
D/CrashAnrDetector( 1017):          9c90bf8c  00000000  
D/CrashAnrDetector( 1017):          9c90bf90  00000000  
D/CrashAnrDetector( 1017):          9c90bf94  00000000  
D/CrashAnrDetector( 1017):          9c90bf98  00000000  
D/CrashAnrDetector( 1017):          9c90bf9c  00000000  
D/CrashAnrDetector( 1017):          9c90bfa0  00000000  
D/CrashAnrDetector( 1017):          9c90bfa4  00000000  
D/CrashAnrDetector( 1017):          9c90bfa8  00000000  
D/CrashAnrDetector( 1017):          9c90bfac  00000000  
D/CrashAnrDetector( 1017):          9c90bfb0  00000000  
D/CrashAnrDetector( 1017):          9c90bfb4  00000000  
D/CrashAnrDetector( 1017):          9c90bfb8  00000000  
D/CrashAnrDetector( 1017):          9c90bfbc  00000000  
D/CrashAnrDetector( 1017):          9c90bfc0  00000000  
D/CrashAnrDetector( 1017):          9c90bfc4 , 00000000  
D/CrashAnrDetector( 1017):          9c90bfc8  00000000  
D/CrashAnrDetector( 1017):          9c90bfcc  00000000  
D/CrashAnrDetector( 1017):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90bfd4  00000000  
D/CrashAnrDetector( 1017):          9c90bfd8  00000000  
D/CrashAnrDetector( 1017):          9c90bfdc  00000000  
D/CrashAnrDetector( 1017):          9c90bfe0  00000000  
D/CrashAnrDetector( 1017):          9c90bfe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90bfe8  e3a070ad  
D/CrashAnrDetector( 1017):          9c90bfec  ef9000ad  
D/CrashAnrDetector( 1017):     #00  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          ........  ........
D/CrashAnrDetector( 1017):     #01  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90bff4  00000000  
D/CrashAnrDetector( 1017):          9c90bff8  00000000  
D/CrashAnrDetector( 1017):          9c90bffc  00000000  
D/CrashAnrDetector( 1017):          9c90c000  00000000  
D/CrashAnrDetector( 1017):          9c90c004  00000000  
D/CrashAnrDetector( 1017):          9c90c008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c00c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c010  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          9c90c014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c018  12dd4780  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          9c90c01c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):          9c90c020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c024  00000000  
D/CrashAnrDetector( 1017):          9c90c028  00000000  
D/CrashAnrDetector( 1017):          9c90c02c  00000000  
D/CrashAnrDetector( 1017):          9c90c030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c034  00000000  
D/CrashAnrDetector( 1017):          9c90c038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c03c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c040  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          9c90c044  73
D/CrashAnrDetector( 1017): processName:com.test.thalitest
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1180):  getBluetoothState : 11
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2706): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService( 2706): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
I/InputMethodManagerService( 1017): [BT Setting State] State =11
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
I/SamsungIME( 1815): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 2706): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/BluetoothAdapterService( 2706): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1180): onStateChanged: Bluetooth
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/BluetoothAdapterService( 2706): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 6080, tid: 6935, name: Thread-1071  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa37a6ff0
D/CrashAnrDetector( 1017):     r0 710804a8  r1 735927c8  r2 12e00890  r3 133c2fc0
D/CrashAnrDetector( 1017):     r4 000000c2  r5 710804a8  r6 735927c8  r7 133c2fc0
D/CrashAnrDetector( 1017):     r8 73592770  r9 b8284ec8  sl 12e00890  fp a38a88a8
D/CrashAnrDetector( 1017):     ip a37a6ff0  sp a37a8ff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1017):     d0  12e00890735927c0  d1  007300200065002f
D/CrashAnrDetector( 1017):     d2  c0c0c0c0c0c0c03c  d3  0102020202020213
D/CrashAnrDetector( 1017):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1017):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1017):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1017):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1017):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1017):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1017):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1017):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1017):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          a37a8f70  00000000  
D/CrashAnrDetector( 1017):          a37a8f74  00000000  
D/CrashAnrDetector( 1017):          a37a8f78  00000000  
D/CrashAnrDetector( 1017):          a37a8f7c  00000000  
D/CrashAnrDetector( 1017):          a37a8f80  00000000  
D/CrashAnrDetector( 1017):          a37a8f84  00000000  
D/CrashAnrDetector( 1017):          a37a8f88  00000000  
D/CrashAnrDetector( 1017):          a37a8f8c  00000000  
D/CrashAnrDetector( 1017):          a37a8f90  00000000  
D/CrashAnrDetector( 1017):          a37a8f94  00000000  
D/CrashAnrDetector( 1017):          a37a8f98  00000000  
D/CrashAnrDetector( 1017):          a37a8f9c  00000000  
D/CrashAnrDetector( 1017):          a37a8fa0  00000000  
D/CrashAnrDetector( 1017):          a37a8fa4  00000000  
D/CrashAnrDetector( 1017):          a37a8fa8  00000000  
D/CrashAnrDetector( 1017):          a37a8fac  00000000  
D/CrashAnrDetector( 1017):          a37a8fb0  00000000  
D/CrashAnrDetector( 1017):          a37a8fb4  00000000  
D/CrashAnrDetector( 1017):          a37a8fb8  00000000  
D/CrashAnrDetector( 1017):          a37a8fbc  00000000  
D/CrashAnrDetector( 1017):          a37a8fc0  00000000  
D/CrashAnrDetector( 1017):          a37a8fc4 , 00000000  
D/CrashAnrDetector( 1017):          a37a8fc8  00000000  
D/CrashAnrDetector( 1017):          a37a8fcc  00000000  
D/CrashAnrDetector( 1017):          a37a8fd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a8fd4  00000000  
D/CrashAnrDetector( 1017):          a37a8fd8  00000000  
D/CrashAnrDetector( 1017):          a37a8fdc  00000000  
D/CrashAnrDetector( 1017):          a37a8fe0  00000000  
D/CrashAnrDetector( 1017):          a37a8fe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a8fe8  e3a070ad  
D/CrashAnrDetector( 1017):          a37a8fec  ef9000ad  
D/CrashAnrDetector( 1017):     #00  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          ........  ........
D/CrashAnrDetector( 1017):     #01  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a8ff4  00000000  
D/CrashAnrDetector( 1017):          a37a8ff8  00000000  
D/CrashAnrDetector( 1017):          a37a8ffc  00000000  
D/CrashAnrDetector( 1017):          a37a9000  00000000  
D/CrashAnrDetector( 1017):          a37a9004  00000000  
D/CrashAnrDetector( 1017):          a37a9008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a900c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9010  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          a37a9014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9018  12e00890  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          a37a901c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):          a37a9020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9024  00000000  
D/CrashAnrDetector( 1017):          a37a9028  00000000  
D/CrashAnrDetector( 1017):          a37a902c  00000000  
D/CrashAnrDetector( 1017):          a37a9030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9034  00000000  
D/CrashAnrDetector( 1017):          a37a9038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a903c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9040  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          a37a9044  73
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/BluetoothBondStateMachine( 2706): make
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 2706): StableState(): Entering Off State
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 2706): handleDebugAction() action=null,
D/BtGatt.GattService( 2706): Received start request. Starting profile...
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/BtGatt.GattService( 2706): start()
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
D/BtGatt.GattService( 2706): start()
I/bluedroid( 2706): get_profile_interface gatt
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
D/BtGatt.AdvertiseManager( 2706): advertise manager created
W/Settings( 1318): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 2458, tid: 2624, name: Thread-256  >>> com.example.hello <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1017):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1017):     r4 9dddde78  r5 9dddde38  r6 b8adc500  r7 9dddde38
D/CrashAnrDetector( 1017):     r8 00000000  r9 9dddde74  sl 9dddf3d0  fp 9dddde1c
D/CrashAnrDetector( 1017):     ip 9d93cba0  sp 9dddde00  lr 9d643308  pc b6f2d468  cpsr 600d0030
D/CrashAnrDetector( 1017):     d0  513802003a373ed5  d1  0000b80c030000a1
D/CrashAnrDetector( 1017):     d2  88000000560a109d  d3  0000003502000060
D/CrashAnrDetector( 1017):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1017):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000012
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1017):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          9ddddd80  00000000  
D/CrashAnrDetector( 1017):          9ddddd84  00000000  
D/CrashAnrDetector( 1017):          9ddddd88  9cd2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9ddddd8c  e8bc0f76  
D/CrashAnrDetector( 1017):          9ddddd90  9dddddbc  [stack:2624]
D/CrashAnrDetector( 1017):          9ddddd94  9dddde64  [stack:2624]
D/CrashAnrDetector( 1017):          9ddddd98  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9ddddd9c  00000003  
D/CrashAnrDetector( 1017):          9ddddda0  9ddddddc  [stack:2624]
D/CrashAnrDetector( 1017):          9ddddda4  b8b162a8  [heap]
D/CrashAnrDetector( 1017):          9ddddda8  9cd53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddac  9da11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddb0  00000000  
D/CrashAnrDetector( 1017):          9dddddb4  ffffff82  
D/CrashAnrDetector( 1017):          9dddddb8  00000000  
D/CrashAnrDetector( 1017):          9dddddbc  ffffff82  
D/CrashAnrDetector( 1017):          9dddddc0  9cd2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddc4  b8b132a8  [heap]
D/CrashAnrDetector( 1017):,          9dddddc8  b8bcbd18  [heap]
D/CrashAnrDetector( 1017):          9dddddcc  00000001  
D/CrashAnrDetector( 1017):          9dddddd0  9cd49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddd4  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9dddddd8  9cd4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9ddddddc  00000000  
D/CrashAnrDetector( 1017):          9ddddde0  00000000  
D/CrashAnrDetector( 1017):          9ddddde4  00000000  
D/CrashAnrDetector( 1017):          9ddddde8  00000003  
D/CrashAnrDetector( 1017):          9dddddec  000000aa  
D/CrashAnrDetector( 1017):          9dddddf0  0000006b  
D/CrashAnrDetector( 1017):          9dddddf4  0001416e  
D/CrashAnrDetector( 1017):          9dddddf8  00000000  
D/CrashAnrDetector( 1017):          9dddddfc  9dddde30  [stack:2624]
D/CrashAnrDetector( 1017):     #00  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1017):          ........  ........
D/CrashAnrDetector( 1017):     #01  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde04  00000000  
D/CrashAnrDetector( 1017):          9dddde08  9dddde78  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde0c  9dddde5c  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde10  9dddde48  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde14  00000000  
D/CrashAnrDetector( 1017):          9dddde18  9dddee94  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde1c  9d61a3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1017):          9dddde20  9dddde50  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde24  00000000  
D/CrashAnrDetector( 1017):          9dddde28  9dddde44  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde2c  9d44c184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1017):          9dddde30  00000000  
D/CrashAnrDetector( 1017):          9dddde34  00000000  
D/CrashAnrDetector( 1017):          9dddde38  b6f73de4  
D/CrashAnrDetector( 1017):          9dddde3c  00000000  
D/CrashAnrDetector( 1017):          9dddde40  9ddde1cc  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde44  9d528b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1017):          9dddde48  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9dddde4c  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9dddde50  b8bcbd18  [heap]
D/CrashAnrDetector( 1017):          9dddde54  00000001  
D/CrashAnrDetector( 1017):          9dddde58  9
D/CrashAnrDetector( 1017): processName:com.example.hello
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1017): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.hid.HidService
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1017): name = block_emergency_message
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.GattService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/HeadsetService( 2706): Received start request. Starting profile...
D/HeadsetService( 2706): start()
W/BluetoothAdapterService( 2706): Not skipping com.broadcom.bt.service.sap.SapService
,I/BluetoothHeadsetServiceJni( 2706): classInitNative: succeeds
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
D/HeadsetStateMachine( 2706): make
D/SettingsProvider( 1017): name = safetycare_geolookout_registering
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2706): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,E/HeadsetStateMachine( 2706): # of Max HF connection is 2
W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 2706): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/ActivityManager( 1017): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1017): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,I/bluedroid( 2706): get_profile_interface handsfree
,I/DualScoManager( 2706): Instantiating Dual Sco Manager
I/DualScoManager( 2706): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 2706): createCMTIContentObservers
,D/SettingsProvider( 1017): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 2706): Enter Disconnected: -2
,D/HeadsetService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/A2dpService( 2706): Received start request. Starting profile...
D/A2dpService( 2706): start()
,D/HeadsetStateMachine( 2706): Clear mHeadsetBrsf
D/HeadsetStateMachine( 2706): map size, before remove : 0
D/HeadsetStateMachine( 2706): map size, after remove: 0
,I/BluetoothAvrcpServiceJni( 2706): classInitNative: succeeds
,I/bluedroid( 2706): get_profile_interface avrcp
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/RemoteController( 2706): Cannot set synchronization mode on an unregistered RemoteController
,D/ConnectivityManager( 2067): CallingUid : 10012, CallingPid : 2067
,D/ConnectivityService( 1017): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1017): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): apparently satisfied.  currentScore=60
,D/ConnectivityService( 1017): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityManager.CallbackHandler( 2067): CM callback handler got msg 524290
,I/Avrcp   ( 2706):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 2706):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 2706): classInitNative: succeeds
D/A2dpStateMachine( 2706): make
,I/bluedroid( 2706): get_profile_interface a2dp
,I/GKI_LINUX( 2706): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 2706): warning : media task started media_task_refcnt 1 
,D/A2dpService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/A2dpStateMachine( 2706): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 2706): classInitNative: succeeds
,D/BluetoothMediaBrowser( 2706): no now playing list
,D/BluetoothMediaBrowser( 2706):  getNowPlayingId now playing id : -1
,D/HidService( 2706): Received start request. Starting profile...
D/HidService( 2706): start()
I/bluedroid( 2706): get_profile_interface hidhost
D/HidService( 2706): setHidService(): set to: null
D/HidService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
I/BluetoothHealthServiceJni( 2706): classInitNative: succeeds
,D/HealthService( 2706): Received start request. Starting profile...
D/HealthService( 2706): start()
,I/bluedroid( 2706): get_profile_interface health
D/HealthService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,I/BluetoothPanServiceJni( 2706): classInitNative(L105): succeeds
,D/PanService( 2706): Received start request. Starting profile...
,D/PanService( 2706): start()
D/BluetoothPanServiceJni( 2706): initializeNative(L110): pan
I/bluedroid( 2706): get_profile_interface pan
,D/PanService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/BluetoothMapService( 2706): Received start request. Starting profile...
,D/BluetoothMapService( 2706): start()
,D/BluetoothMapService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/[LPC]   ( 1017): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,I/BluetoothSAPServiceJni( 2706): classInitNative(L204): succeeds
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/SapService( 2706): Received start request. Starting profile...
D/SapService( 2706): start()
D/BluetoothSAPServiceJni( 2706): initializeNative(L209): sap
I/bluedroid( 2706): get_profile_interface sap
D/SapService( 2706): mStartError = false
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/HeadsetStateMachine( 2706): Try to query the phonestate on bind
,I/Telecom ( 1434): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1434): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1434): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1434): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1434): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Telecom ( 1434): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1434): Proxy not attached to service
D/HeadsetStateMachine( 2706): Proxy object connected
I/Telecom ( 1434): BluetoothPhoneService: Result of Message : true
,D/HeadsetPhoneState( 2706): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 2706): sendDeviceDataStateChanged
D/HeadsetStateMachine( 2706): Disconnected process message: 11
D/HeadsetPhoneState( 2706): Signal level : previous=0 curr=0
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 2706): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 2706): Proxy object connected
D/BluetoothAdapterService( 2706): Bluetooth A2dp source service connected
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,D/HeadsetStateMachine( 2706): Disconnected process message: 18
,D/HeadsetStateMachine( 2706): Disconnected process message: 10
D/HeadsetPhoneState( 2706): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,E/Zygote  ( 2790): MountEmulatedStorage()
I/libpersona( 2790): KNOX_SDCARD checking this for 1000,
E/Zygote  ( 2790): v2
I/libpersona( 2790): KNOX_SDCARD not a persona
D/HeadsetStateMachine( 2706): Disconnected process message: 11
I/SELinux ( 2790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2790 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
E/SELinux ( 2790): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2807): MountEmulatedStorage(),
E/Zygote  ( 2807): v2
I/libpersona( 2807): KNOX_SDCARD checking this for 10145
I/libpersona( 2807): KNOX_SDCARD not a persona
I/SELinux ( 2807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2807 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 2807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2790): TimaSignature is unavailable
,D/ActivityThread( 2790): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2807): TimaSignature is unavailable
,D/ActivityThread( 2807): Added TimaKeyStore provider
,W/ResourcesManager( 2790): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2807): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 2807): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 2807): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 2807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2807): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,W/CursorWrapperInner( 2342): Cursor finalized without prior close()
,I/i       ( 1017): No model
,D/FactoryTest( 1017): Not factory mode
D/FactoryTest( 1017): Not factory mode. isFactoryMode() returend false
D/w       ( 1017): isUserBuild = true
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,D/SSRM:aZ ( 1017): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1017): Updating Threshold Value.. isSystemReady: true
,E/SmartFaceService( 1017): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1017): no icon
E/SmartFaceService( 1017): mActiveServiceType: 0
E/SmartFaceService( 1017): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1017): updateClientsDone. def. do nothing.
E/SmartFaceService( 1017): Service Type to Worker: 0
E/SmartFaceService( 1017): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1017): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/BluetoothA2dp( 1017): Proxy object connected
,D/BluetoothPan( 1017): BluetoothPAN Proxy object connected
,V/AlarmManagerEXT( 1017): mGmsLocationBundling: false
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1017): [SO] activate (ident=0xb86611f8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb86611f8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,W/DriveInitializer( 2067): Awaiting to be initialized
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,W/DriveInitializer( 2067): Background init thread started
,I/ActivityManager( 1017): Killing 1191:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 1400:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/RCPManagerService( 1017): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1017):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/RCPManagerService( 1017): BootReceiver.onReceive(): Starting RCP Proxy for user = null
E/RCPManagerService( 1017):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/SSRM:n  ( 1017): SIOP:: AP = 340
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb86611f8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb85ce4c0, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/EnterpriseDeviceManagerService( 1017): android.intent.action.BOOT_COMPLETED
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2067): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,V/ApplicationPolicy( 1017): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1017): refresh widget status for user 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1191/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1400/cgroup.procs: No such file or directory
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,D/EnterpriseDeviceManagerService( 1017): runAdminUpdate
,D/EnterpriseUtils( 1017): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1017): nothing to selfUpdate
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 27
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/PhoneRestrictionPolicy( 1017): Message received - msg { when=-5ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1017): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy( 1017): MSG_REMOVE_ORPHANED_CONTAINERS received
,D/WifiP2pService( 1017): InactiveState{ what=143415 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143415 }
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
D/WifiP2pService( 1017): DefaultState{ what=143415 }
,D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI_P2P
,W/PhoneRestrictionPolicy( 1017): cvList size 0
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
,D/WIFI_P2P( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,W/PhoneRestrictionPolicy( 1017): cvList size 0
,D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI
D/Tethering( 1017): Boot complete.,
,E/WifiStateMachine( 1017): Blacklist file delete
,D/SensorService( 1017): [SO] currT = 33920076652, prevT = 33590089204, diff = 329987448, [0.057 0.153 10.113]
D/SensorService( 1017): [SO] 0.057 0.153 10.113
D/SensorService( 1017): [SO] [100 -> 255]
,V/EnterpriseBillingEngine( 1017): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1017): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - end - null
,V/EnterpriseBillingEngine( 1017): handleAllprofiles - end
,D/UsbHostNotification( 1017): boot completed
,I/art     ( 1017): Background sticky concurrent mark sweep GC freed 51384(3MB) AllocSpace objects, 121(9MB) LOS objects, 32% free, 27MB/40MB, paused 14.898ms total 256.999ms
,D/UsbHostRestrictor( 1017): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1017): initSetUsbBlock STARTED
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/UsbHostRestrictor( 1017): SIM was never inserted
,D/UsbHostRestrictor( 1017): writableHostSysNode[false]
D/UsbHostRestrictor( 1017): Can NOT Write Disable Sys Node to [ON]
,D/WIFI    ( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/PersonaManagerService( 1017): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1017):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1017): onBootComplete
,W/DriveInitializer( 2067): Background init thread ended
,D/UsbStorageNotification( 1017): boot completed
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1017): set_capabilities_callback: 55u
I/libmdmdetect( 1017): ESOC framework not supported
I/KnoxKeyguardUpdateMonitor( 1017): onTrustManagedChanged user 0, managed:false
I/libmdmdetect( 1017): Found internal modem: modem
E/PerMgrLib( 1017): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 ,
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_cleanup 
I/KnoxKeyguardUpdateMonitor( 1017): onTrustChanged user:0, enable:false
D/KeyguardViewMediator( 1180): onTrustChanged( Showing = false , userId = 0 )
,D/StorageNotification( 1180): boot completed
,D/qmi_secgps_clnt( 1017): qmi_secgps_client_init()
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1017): Killing 1525:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BluetoothAdapterState( 2706): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2706): enable
,I/bt_hci_bdroid( 2706): init
,D/BadgeProvider( 1563): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/GKI_LINUX( 2706): gki_task_entry task_id=0 [BTU] starting
,D/StatusBarManagerService( 1017): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/PhoneStatusBar( 1180): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1017): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,I/bt_vendor( 2706): bt-vendor : init
,I/bt_vendor( 2706): bt-vendor : get_bt_soc_type
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/bt_vendor( 2706): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 2706): init: Local BD Address : ab:96:37:0e:f9:7c
D/bt_userial_mct( 2706): userial_init
,I/bt_vendor( 2706): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2706): Starting hciattach daemon
I/bt_vendor( 2706): try to set false
,I/bt_vendor( 2706): bt-vendor : BT_VND_OP_POWER_CTRL: On,
I/bt_vendor( 2706): Starting hciattach daemon
I/bt_vendor( 2706): try to set true
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/Zygote  ( 2864): MountEmulatedStorage()
,E/Zygote  ( 2864): v2
I/libpersona( 2864): KNOX_SDCARD checking this for 10099
I/libpersona( 2864): KNOX_SDCARD not a persona
,I/SELinux ( 2864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2864 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2864): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/qcom-bluetooth( 2870): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/Launcher.Model( 1481): reloadBadges entered.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 1563): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1563): sendNotify, [notify] : null
D/BadgeProvider( 1563): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1563): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1563): update, [UpdateCount] : 1
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1525/cgroup.procs: No such file or directory
,E/LocSvc_utils_cfg( 1017): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,D/TimaKeyStoreProvider( 2864): TimaSignature is unavailable
,D/ActivityThread( 2864): Added TimaKeyStore provider
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1017): SECGPS: Set AGPS Mode : 7
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,I/qcom-bluetooth( 2889): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 1797:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
I/qcom-bluetooth( 2890): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,I/qcom-bluetooth( 2894): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 2895): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 2896): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 2897): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1797/cgroup.procs: No such file or directory
,I/dhcpcd  ( 2181): wlan0: sending IPv6 Router Solicitation
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
E/ActivityThread( 2864): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 2864): Failed to find provider info for flipboard.auth.internal
I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
I/ActivityManager( 1017): Killing 1679:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
I/System.out( 1017): start Service
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2905): MountEmulatedStorage()
,E/Zygote  ( 2905): v2
I/libpersona( 2905): KNOX_SDCARD checking this for 1000
I/libpersona( 2905): KNOX_SDCARD not a persona
,I/SELinux ( 2905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2905 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2919): MountEmulatedStorage()
I/libpersona( 2919): KNOX_SDCARD checking this for 10152
E/Zygote  ( 2919): v2
I/libpersona( 2919): KNOX_SDCARD not a persona
,I/SELinux ( 2919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qcom-bluetooth( 2922): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
D/TimaKeyStoreProvider( 2905): TimaSignature is unavailable,
D/ActivityThread( 2905): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2919 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,D/ActivityManager( 1017): startService callerProcessName:android, calleePkgName: android
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10107/pid_1679/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/qcom-bluetooth( 2929): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 2919): TimaSignature is unavailable
D/ActivityThread( 2919): Added TimaKeyStore provider
,W/ResourcesManager( 2905): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 1521
D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 1521
D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
D/BluetoothBDAdrressReceiver( 2905): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1459): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/bt_vendor( 2706): bluetooth satus is on
,D/bt_userial_mct( 2706): userial_open(port:0)
I/bt_vendor( 2706): bt-vendor : BT_VND_OP_USERIAL_OPEN
D/BluetoothBDTestService( 1459): onCreate()
,E/Zygote  ( 2942): MountEmulatedStorage()
,I/libpersona( 2942): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 2942): v2
I/libpersona( 2942): KNOX_SDCARD not a persona
I/bt_vendor( 2706): Done intiailizing UART
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2942 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/bt_vendor( 2706): Done intiailizing UART
I/bt_userial_mct( 2706): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2706): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 2706): Entering userial_read_thread()
E/BluetoothBDTestService( 1459): onStart(), extra_type: BOOT_COMPLETED
,E/BluetoothBDTestService( 1459): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1459): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/SELinux ( 2942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Killing 1498:com.android.printspooler/u0a136 (adj 15): empty #31,
,I/SELinux ( 2942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/        ( 2706): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2706): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2706): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2706): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2706): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2706): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2706): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2706): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2706): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2706): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2706): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2706): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2706): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2706): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2706): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2706): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2706): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/SELinux ( 2942): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
,I/ANDROID_DRM_FRWORKS_DrmManager(  281): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,I/art     (  302): Explicit concurrent mark sweep GC freed 8796(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 687us total 21.615ms
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/CscReceiver( 1459): onReceive android.intent.action.BOOT_COMPLETED
,E/SQLiteLog( 2919): (284) automatic index on shooting_modes(title_id)
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 18.280ms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1459): onStart
E/CscUpdateService( 1459): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1459): set_CSC_version
,E/CscParser( 1459): update(): xml file exist
,D/TimaKeyStoreProvider( 2942): TimaSignature is unavailable
D/ActivityThread( 2942): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.138ms
,E/Zygote  ( 2959): MountEmulatedStorage()
E/Zygote  ( 2959): v2
I/libpersona( 2959): KNOX_SDCARD checking this for 10003
I/libpersona( 2959): KNOX_SDCARD not a persona
,I/SELinux ( 2959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2959 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/CscUtil ( 1459): isWifiOnly = false
I/System.out( 1459): HandDataNode = null
,I/CscUpdateService( 1459): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1459): This is normal boot : CSC not updated
,D/ActivityManager( 1017): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,W/bt-l2cap( 2706): l2c_link_processs_ble_num_bufs 16
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/bt-btm  ( 2706): BTM_SecRegister:p_cb_info->p_le_callback == 0xa401c6e9 
E/bt-btm  ( 2706): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa401c6e9 
,E/CscParser( 1459): update(): xml file exist
,W/ResourcesManager( 2942): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2979): MountEmulatedStorage()
E/Zygote  ( 2979): v2
I/libpersona( 2979): KNOX_SDCARD checking this for 1101
I/libpersona( 2979): KNOX_SDCARD not a persona
D/BluetoothAdapterProperties( 2706): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0,
I/SELinux ( 2979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/bt-btif ( 2706): Calling BTA_HhEnable
,E/bt-btif ( 2706): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 2706): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 2706): populateRssiValuesNative,
I/bluedroid( 2706): getModelRssiValues
E/BluetoothServiceJni( 2706): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2706): modelRssiValuesCallback, low, mid, high = -70,-60,127
,I/SELinux ( 2979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/CscGPS  ( 1459): CSCGPS.updateParameters
D/CscGPS  ( 1459): supl host : null
D/CscGPS  ( 1459): SUPL Host is null or invalid
D/CscGPS  ( 1459): supl_ver : null
D/CscGPS  ( 1459): SUPL Ver is null or invalid
E/SELinux ( 2979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CscGPS  ( 1459): supl port : null
D/CscGPS  ( 1459): SUPL PORT is null or invalid
D/CscGPS  ( 1459): LPP : null
D/CscGPS  ( 1459): LPP is null or invalid
D/CscGPS  ( 1459): CSC don't have any AGPS value.
,D/TimaKeyStoreProvider( 2959): TimaSignature is unavailable
,D/ActivityThread( 2959): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2979 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,I/CscUpdateService( 1459): same CSC Version
D/CscUtil ( 1459): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
,D/BluetoothAdapterProperties( 2706): Name is: A5-1
,D/TimaKeyStoreProvider( 2979): TimaSignature is unavailable
D/SettingsProvider( 1017): name = bluetooth_name
D/ActivityThread( 2979): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1498/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/BluetoothUtils( 2706): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2706): Scan Mode:20
D/BluetoothAdapterProperties( 2706): Discoverable Timeout:120
D/BluetoothAdapterProperties( 2706): LE Address is:FC:F3:1C:6E:2D:57
E/bt-btif ( 2706): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2706): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2706): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2706): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2706): db_open: file /etc/bluetooth/iop_bt.db
E/bt_mct  ( 2706): hci lib postload completed
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
,D/IOP_DB_BT( 2706): db_open: db_open : handle 3027820560l, read 13894 bytes onto local cache
D/IOP_DB_BT( 2706): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/IOP_DB_BT( 2706): db_query: result 1
I/        ( 2706): iop_db_open: iop_db_open status 0
,W/ResourcesManager( 2979): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 2942): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 2942): savePreference: key = previous_sys_time value = 1452528589709
,I/KnoxUsageLogPro( 2942): premStatus:2
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
V/SmartcardService( 2979): main Received broadcast
V/SmartcardService( 2979): Starting smartcard service after boot completed
I/KnoxUsageLogPro( 2942): isEulaShown : false
I/KnoxUsageLogPro( 2942): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2999): MountEmulatedStorage(),
I/libpersona( 2999): KNOX_SDCARD checking this for 10085
E/Zygote  ( 2999): v2
I/libpersona( 2999): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2999 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2122:com.vlingo.midas/u0a31 (adj 15): empty #31
D/ActivityManager( 1017): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1017): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,D/bte_conf( 2706): Device ID record 1 : primary
D/bte_conf( 2706):   vendorId            = 0075
D/bte_conf( 2706):   vendorIdSource      = 0001
D/bte_conf( 2706):   product             = 0100
D/bte_conf( 2706):   version             = 0200
D/bte_conf( 2706):   clientExecutableURL = 
D/bte_conf( 2706):   serviceDescription  = 
D/bte_conf( 2706):   documentationURL    = 
D/bte_conf( 2706): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2706): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,I/SELinux ( 2999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Killing 2151:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
I/SELinux ( 2999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapterState( 2706): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2706): ScanMode =  20
D/BluetoothAdapterProperties( 2706): State =  11
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 2706): Setting state to 12
I/BluetoothAdapterState( 2706): Bluetooth adapter state changed: 11-> 12
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 28
,I/KnoxUsageLogPro( 2942): savePreference: key = previous_elapsed_time value = 34771
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/BluetoothUtils( 2706): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2706): Scan Mode:21
D/BluetoothAdapterProperties( 2706): Discoverable Timeout:120
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/TP/MmsProvider( 1459): Update uri=content://mms, match=0
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
D/TP/MmsProvider( 1459): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Zygote  ( 3015): MountEmulatedStorage()
I/libpersona( 3015): KNOX_SDCARD checking this for 10157
E/Zygote  ( 3015): v2
I/libpersona( 3015): KNOX_SDCARD not a persona
,I/SELinux ( 3015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 2706): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2706): updateAdapterState state is 12
,I/SELinux ( 3015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3015 uid=10157 gids={50157, 9997} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/Mms:transaction( 2342): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2342): [start]    nonBlockingUpdateMessageIndicator() consume time = 3262.619374
,D/BluetoothAdapterService( 2706): Autoconnection is available 
I/Mms/ReservationManager( 2342): resetAfterConnected()
D/BluetoothAdapterService( 2706): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2706): starting service from this receiver
D/BluetoothAdapter( 1434): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1434): onBluetoothStateChange: Bluetooth is on
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothAdapterState( 2706): Entering On State from state = 11
D/BluetoothAdapter( 2706): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2706): onBluetoothStateChange: Bluetooth is on
,D/Mms/MessagingNotification( 2342): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2342): isDefault true
,D/TP/MmsProvider( 1459): Query uri=content://mms, match=0, calling pid = 2342
,D/TimaKeyStoreProvider( 2999): TimaSignature is unavailable
D/ActivityThread( 2999): Added TimaKeyStore provider
,E/BluetoothManagerService( 1017): Unable to call onBluetoothStateChange() on callback #3
E/BluetoothManagerService( 1017): android.os.DeadObjectException
E/BluetoothManagerService( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothManagerService( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothManagerService( 1017): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1067)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2021)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
E/BluetoothManagerService( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService( 1017): 	at android.os.Looper.loop(Looper.java:145)
E/BluetoothManagerService( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothManagerService( 1017): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/TP/MmsSmsProvider( 1459): query,matched:7, calling pid = 2342
D/BluetoothAdapter( 1446): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1446): onBluetoothStateChange: Bluetooth is on
D/TP/MmsSmsProvider( 1459): match 7:Elapsed time : 1.391 ms
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/BluetoothPbapService( 2706): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothAdapter( 1180): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1180): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1846): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1846): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1459): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1459): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 2437): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2437): onBluetoothStateChange: Bluetooth is on
,D/TimaKeyStoreProvider( 3015): TimaSignature is unavailable
D/BluetoothA2dp( 1017): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1017): onBluetoothStateChange: up=true
D/ActivityThread( 3015): Added TimaKeyStore provider
,D/BluetoothAdapter( 1017): onBluetoothStateChange: Bluetooth is on
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/BluetoothA2dp( 2706): onBluetoothStateChange: up=true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1017): [BT Setting State] State =12
I/InputMethodManagerService( 1017): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothHeadset( 1434): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3e581387, true
D/BluetoothTile( 1180):  onBluetoothStateChange:
,D/BluetoothHeadset( 1434): registerMessageListener
E/SQLiteLog( 1227): (283) recovered 662 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,I/SamsungIME( 1815): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
W/ResourcesManager( 2999): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ResourcesManager( 2999): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/BluetoothTile( 1180):  getBluetoothState : 12
W/ResourcesManager( 2999): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2999): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2999): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2999): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/BluetoothPbapService( 2706): Handler(): got msg=1
,W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2122/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2151/cgroup.procs: No such file or directory
D/HeadsetService( 2706): registerMessageListener
,I/SecureStorage( 2959): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
I/Telecom ( 1434): BluetoothPhoneService: handleMessage(7) / param null
D/HeadsetService( 2706): registerMessageListener
I/Telecom ( 1434): BluetoothPhoneService: updateHeadsetWithCallState
D/HeadsetStateMachine( 2706): Disconnected process message: 70
D/HeadsetStateMachine( 2706): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@29654d11
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,W/ResourcesManager( 3015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/Mms/ReservationManager( 2342): getReservedSendMessageCount(): retMessageCount=0
D/BluetoothTile( 1180):  handleUpdatestate:false name:null
I/Telecom ( 1434): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1434): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1434): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/TP/MmsSmsProvider( 1459): query,matched:200, calling pid = 2342
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1459): match 200:Elapsed time : 3.004 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/HeadsetStateMachine( 2706): Disconnected process message: 9
,D/HeadsetStateMachine( 2706): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/BluetoothPbapService( 2706): PBAP Service initSocket try: 0
,E/Zygote  ( 3038): MountEmulatedStorage()
E/Zygote  ( 3038): v2
I/libpersona( 3038): KNOX_SDCARD checking this for 1000
D/BluetoothMapMasInstance( 2706): set MAP SDP message type : 1
I/libpersona( 3038): KNOX_SDCARD not a persona
I/SELinux ( 3038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SecureStorage( 2959): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  355): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2959
I/SecureStorage(  355): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,I/SecureStorage( 2959): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2959): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  355): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2959
I/SecureStorage(  355): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,D/BluetoothSocket( 2706): bindListen(): myUserId = 0
W/BluetoothAdapter( 2706): getBluetoothService() called with no BluetoothManagerCallback
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
D/audio_hw_primary(  282): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  282): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,E/HeadsetStateMachine( 2706): terminateScoUsingVirtualVoiceCall:No present call to terminate
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3038): TimaSignature is unavailable
,D/ActivityThread( 3038): Added TimaKeyStore provider
,E/Zygote  ( 3053): MountEmulatedStorage()
,E/Zygote  ( 3053): v2
I/libpersona( 3053): KNOX_SDCARD checking this for 10048
I/libpersona( 3053): KNOX_SDCARD not a persona
,I/SELinux ( 3053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3053 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3053): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothSocket( 2706): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2706): bindListen(), new LocalSocket 
D/BluetoothSocket( 2706): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2706): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29c32e76
,D/BluetoothSocket( 2706): channel: 19
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
D/BluetoothPbapService( 2706): PBAP Socket is BluetoothServerSocket
,D/BluetoothSocket( 2706): bindListen(): myUserId = 0
W/BluetoothAdapter( 2706): getBluetoothService() called with no BluetoothManagerCallback
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3053): TimaSignature is unavailable
D/ActivityThread( 3053): Added TimaKeyStore provider
,E/Zygote  ( 3069): MountEmulatedStorage()
E/Zygote  ( 3069): v2
I/libpersona( 3069): KNOX_SDCARD checking this for 10159
I/libpersona( 3069): KNOX_SDCARD not a persona
,I/SELinux ( 3069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3069 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3069): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2227:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,D/BluetoothSocket( 2706): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2706): bindListen(), new LocalSocket 
D/BluetoothSocket( 2706): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2706): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2586ec77
D/BluetoothSocket( 2706): channel: 5
,D/Mms/SmsReceiverService( 2342): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/MediaScanner( 1227): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/Mms/TelephonyPermission( 2342): isDefault true
D/Mms/SmsReceiverService( 2342): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2342): [start]    handleBootCompleted() consume time = 205.368333
,D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2342
,D/TP/SmsProvider( 1459): match 0:Elapsed time : 2.279 ms
,W/ResourcesManager( 3053): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3053): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3053): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3069): TimaSignature is unavailable
,D/ActivityThread( 3069): Added TimaKeyStore provider
,D/TP/SmsProvider( 1459): query,matched:51, calling pid = 2342
,D/TP/SmsProvider( 1459): match 51:Elapsed time : 2.359 ms
,D/TP/MmsSmsProvider( 1459): getThreadUnReadCount unreadCount=0 imUnreadCount=0
,D/TP/MmsSmsProvider( 1459): deleteConversation threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1459): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1459): updateThread(), thread_id = 9223372036854775806
,D/Mms/MessagingNotification( 2342): isBlockingModeEnabled() = false, Zen mode = 0
,E/SQLiteLog( 3038): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,V/TP/MmsSmsDatabaseHelper( 1459): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
,I/Intent to TravelDirActivity( 3069): inside TravelBroadcastReceiver
,D/TP/MmsSmsProvider( 1459): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
,V/MediaScanner( 1227): processDirectory :  /system/media
,D/Mms/Conversation( 2342): deleteTempConversation(),deleted=0
,V/MediaScanner( 1227):  prescan time: 427ms (DB items: 141)
V/MediaScanner( 1227):     scan time: 48ms (Caching mode: true), (makeEntry time: 18ms ~37%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 475ms
V/MediaScanner( 1227): checked files: 133  directories : 6  (I: 0, U: 0)
,D/MediaScanner( 1227): checkDefaultSounds
,D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
,W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2227/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 22882(1294KB) AllocSpace objects, 4(336KB) LOS objects, 33% free, 26MB/39MB, paused 2.314ms total 238.403ms
,D/BadgeProvider( 1563): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/DSM     ( 3038): [Lines:107] Normal booted
D/DSM     ( 3038): [Lines:114] Boot completed
,D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
,E/Zygote  ( 3087): MountEmulatedStorage()
I/libpersona( 3087): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3087): v2
I/libpersona( 3087): KNOX_SDCARD not a persona
,I/SELinux ( 3087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3087): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/SettingsProvider( 1017): name = block_emergency_message
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1563): sendNotify entered. [uri] : content://com.sec.badge/apps/2
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1563): sendNotify, [notify] : null
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1563): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1563): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1563): update, [UpdateCount] : 1
D/Launcher.Model( 1481): reloadBadges entered.
,D/SmsProvider( 1459): Update uri=content://sms/outbox, match=8
,D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
,D/TimaKeyStoreProvider( 3087): TimaSignature is unavailable
D/ActivityThread( 3087): Added TimaKeyStore provider
,E/Zygote  ( 3102): MountEmulatedStorage()
E/Zygote  ( 3102): v2
I/libpersona( 3102): KNOX_SDCARD checking this for 1000
I/libpersona( 3102): KNOX_SDCARD not a persona
,I/SELinux ( 3102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 1613:com.google.android.partnersetup/u0a15 (adj 15): empty #31,
,W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/Mms/MessagingNotification( 2342): setBadgeCount(), count=0
,D/FactoryTestApp( 2682): [DummyFtClient$mBroadcastReceiver](2682) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2682): [DummyFtClient$mBroadcastReceiver](2682) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2682): [DummyFtClient$mBroadcastReceiver](2682) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/TimaKeyStoreProvider( 3102): TimaSignature is unavailable
,D/ActivityThread( 3102): Added TimaKeyStore provider
D/MediaScannerService( 1227): !@done scanning volume internal
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/Mms/SmsReceiverService( 2342): moveOutboxMessagesToFailedBox messageCount: 0
,D/Mms/SmsReceiverService( 2342): handle boot completed, sendFirstQueuedMessage()
,D/Mms/SmsReceiverService( 2342): [SIM-1]sendFirstQueuedMessage()
,D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Mms/MessagingNotification( 2342): remove alarm
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,I/ActivityManager( 1017): Killing 2325:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2342
,D/TP/SmsProvider( 1459): query,matched:26, calling pid = 2342
,D/TP/SmsProvider( 1459): match 0:Elapsed time : 0.074 ms
,D/Mms/MessagingNotification( 2342): [end]    nonBlockingUpdateMessageIndicator() consume time = 481.270208
,W/ResourcesManager( 3102): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1459): match 26:Elapsed time : 38.646 ms
D/ActivityManager( 1017): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,I/WifiCredService( 1318): onCreate
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3120 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2380:com.sec.android.omc/1000 (adj 15): empty #31,
E/Zygote  ( 3120): MountEmulatedStorage()
E/Zygote  ( 3120): v2
I/libpersona( 3120): KNOX_SDCARD checking this for 10160
I/libpersona( 3120): KNOX_SDCARD not a persona
I/SELinux ( 3120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/MessagingNotification( 2342): updateAllHistoryAsRead()
,E/SELinux ( 3120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiTimerReceiver( 1318): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1318): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1318): Action boot completed received
W/ActivityThread( 3102): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/WifiCredService( 1318): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiStateMachine( 1017): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1017): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1017): invaild command id : 215
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/Mms/SmsReceiver( 2342): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2342): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2342): isDefault true
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
I/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,D/NearbySettings( 1318): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1318): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1318): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,D/TimaKeyStoreProvider( 3120): TimaSignature is unavailable
,D/ActivityThread( 3120): Added TimaKeyStore provider
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2325/cgroup.procs: No such file or directory
,D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,D/TP/MmsProvider( 1459): Query uri=content://mms, match=0, calling pid = 2342
,W/art     ( 2999): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 175.019ms
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,I/NearbySettings( 1318): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1318): MountReceiver.onReceive - Internal Path
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1613/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2380/cgroup.procs: No such file or directory
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
,D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/HeadsetService( 2706): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2706): Disconnected process message: 10
,W/ResourcesManager( 3120): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/SettingsProvider( 1017): name = personal_mode_enabled
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT,
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
E/USB_UICC(  295): Timeout! No signal received. Retry num = 29
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 3102): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/SecureStorage(  355): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,I/LcdtestApp( 3102): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/Zygote  ( 3139): MountEmulatedStorage()
,E/Zygote  ( 3139): v2
I/libpersona( 3139): KNOX_SDCARD checking this for 1000
I/libpersona( 3139): KNOX_SDCARD not a persona
,I/SELinux ( 3139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2397:com.sec.tcpdumpservice/1000 (adj 15): empty #31
I/SELinux ( 3139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 1459): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SecureStorage( 2959): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2959): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,I/art     (  302): Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 30.500ms
,D/TimaKeyStoreProvider( 3139): TimaSignature is unavailable
,D/ActivityThread( 3139): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 18.458ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.589ms
,V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1227):  prescan time: 171ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 15ms (Caching mode: true), (makeEntry time: 12ms ~80%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 188ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2397/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 2437): disable()
,D/MediaScannerService( 1227): !@done scanning volume external
,D/FactoryTestApp( 2682): [DummyFtClient$mBroadcastReceiver](2682) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 2682): [DummyFtClient$mBroadcastReceiver](2682) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2682): [DummyFtClient$sendBootCompletedAndFinish](2682) ...
D/FactoryTestApp( 2682): [Support$Values.getString](2682) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2682): [ModuleCommon$isConnectionModeNone](2682) mConnectionMode = gsm
,D/SettingsProvider( 1017): name = bluetooth_on
,D/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$ResponseWriter](2682) Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$connectToSecPhoneService](2682)  
,W/ContextImpl( 2682): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/ActivityManager( 1017): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,I/art     ( 1459): Background sticky concurrent mark sweep GC freed 40511(2MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 8MB/11MB, paused 3.608ms total 126.603ms
I/art     ( 1459): WaitForGcToComplete blocked for 127.022ms for cause Explicit
,I/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$onServiceConnected](2682) connected done
D/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$write](2682) Send Response Message to SecPhone
D/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$write](2682) Response ��
D/[0]UMC:UMCContentProvider( 3120): @onCreate
,D/AT_Distributor(  313): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,D/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$handleMessage](2682) Send BOOTING COMPLETED done
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 1933(100KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 863us total 32.816ms
,D/[0]UMC:Core( 3120): onCreate(): 
D/[0]UMC:Core( 3120): @isManagedProfileUser
D/[0]UMC:Core( 3120): userId: 0
,D/TP/MmsSmsProvider( 1459): query,matched:200, calling pid = 2342
,D/TP/MmsSmsProvider( 1459): match 200:Elapsed time : 0.825 ms
,D/[0]UMC:Core( 3120): userInfo: UserInfo{0:Thali Test:13}
,D/[0]UMC:Core( 3120): userInfo.isManagedProfile() : false
,I/SmartcardBootCompleteReceiver( 1318): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1318): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2342
,D/TP/SmsProvider( 1459): match 0:Elapsed time : 1.773 ms
,D/TP/SmsProvider( 1459): query,matched:51, calling pid = 2342
,D/TP/SmsProvider( 1459): match 51:Elapsed time : 0.777 ms
,D/Mms/MessagingNotification( 2342): isBlockingModeEnabled() = false, Zen mode = 0
,D/BadgeProvider( 1563): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SmartcardBootCompleteReceiver( 1318): Broadcast sent with current lockscreen type
,I/DIAGMON_AGENT( 3139): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/[0]UMC:DeviceInfo( 3120): USA==US==
,D/AT_Distributor(  313): SetAtdStatus(), 1_1_0
D/AT_Distributor(  313): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/BluetoothMediaBrowser( 2706):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/BluetoothMediaBrowser( 2706): no now playing list
D/BluetoothMediaBrowser( 2706):  getNowPlayingId now playing id : -1
,D/Launcher.Model( 1481): reloadBadges entered.
,D/BadgeProvider( 1563): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1563): sendNotify, [notify] : null
D/BluetoothAdapterState( 2706): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 2706): Setting state to 13
I/BluetoothAdapterState( 2706): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2706): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2706): updateAdapterState state is 13
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/BadgeProvider( 1563): update, [uri] : content://com.sec.badge/apps/2
I/BluetoothPbapService( 2706): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/WifiService( 1017): setWifiEnabled: false pid=2437, uid=10177
D/BluetoothAdapterService( 2706): Autoconnection is available 
D/BluetoothAdapterService( 2706): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 2706): terminating service from this receiver
D/SettingsProvider( 1017): name = wifi_on
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
D/BadgeProvider( 1563): update, [BadgeCount] : badgecount=0
D/BluetoothSocket( 2706): close() in, this: android.bluetooth.BluetoothSocket@318920e4, channel: 19, state: LISTENING
D/BluetoothSocket( 2706): close() this: android.bluetooth.BluetoothSocket@318920e4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29c32e76, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33c0a94dmSocket: android.net.LocalSocket@3b2bbc02 impl:android.net.LocalSocketImpl@3073d913 fd:FileDescriptor[74]
D/BluetoothSocket( 2706): Closing mSocket: android.net.LocalSocket@3b2bbc02 impl:android.net.LocalSocketImpl@3073d913 fd:FileDescriptor[74]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2706): onBluetoothDisable()
D/BluetoothAdapterProperties( 2706): mDiscovering is false
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2706): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BadgeProvider( 1563): update, [UpdateCount] : 1
,D/BluetoothUtils( 2706): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 2706): Scan Mode:20
,D/BluetoothAdapterState( 2706): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2706): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2706): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 2706): cmd socket is not created
,I/jxcore-log( 2437): ****TEST TOOK:  5232  ms ****
I/jxcore-log( 2437): 
,E/bt-btm  ( 2706): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 2706): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 2706): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2706): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2706): L2CAP - PSM: 0x001b not found for deregistration
D/Mms/MessagingNotification( 2342): setBadgeCount(), count=0
,I/jxcore-log( 2437): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2437): 
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2037): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2037): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2037): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2037): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/[SBeam] ( 1318): SBeamEnabler.initPreferenceForSbeam : 0
D/Mms/MessagingNotification( 2342): remove alarm
,D/Mms/MessagingNotification( 2342): updateAllHistoryAsRead()
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1017): [BT Setting State] State =13
,D/BluetoothTile( 1180):  onBluetoothStateChange:,
,D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1180):  getBluetoothState : 13
,I/SamsungIME( 1815): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,D/BluetoothSocket( 2706): close() in, this: android.bluetooth.BluetoothSocket@27fb8d49, channel: 5, state: LISTENING
,D/BluetoothSocket( 2706): close() this: android.bluetooth.BluetoothSocket@27fb8d49, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2586ec77, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a9d964emSocket: android.net.LocalSocket@738f36f impl:android.net.LocalSocketImpl@2445a87c fd:FileDescriptor[76]
D/BluetoothSocket( 2706): Closing mSocket: android.net.LocalSocket@738f36f impl:android.net.LocalSocketImpl@2445a87c fd:FileDescriptor[76]
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/SettingSearch/SearchIntentReceiver( 1318): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1318): search setting db init!!
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/ContextImpl( 1318): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2342
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Bluetooth
,I/SettingSearch/SearchIntentReceiver( 1318): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/TP/SmsProvider( 1459): match 0:Elapsed time : 6.032 ms
,D/Mms/SmsReceiverService( 2342): [end]    handleBootCompleted() consume time = 678.304219
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3171 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3171): MountEmulatedStorage()
E/Zygote  ( 3171): v2
I/libpersona( 3171): KNOX_SDCARD checking this for 1000
I/libpersona( 3171): KNOX_SDCARD not a persona
,I/SELinux ( 3171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3179): MountEmulatedStorage(),
E/Zygote  ( 3179): v2,
I/libpersona( 3179): KNOX_SDCARD checking this for 10150
I/libpersona( 3179): KNOX_SDCARD not a persona
,I/SELinux ( 3179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3179 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,E/SELinux ( 3179): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,E/ConnectivityService( 1017): updateNetworkInfo(),
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/TimaKeyStoreProvider( 3179): TimaSignature is unavailable
,D/ActivityThread( 3179): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3171): TimaSignature is unavailable
D/ActivityThread( 3171): Added TimaKeyStore provider
,D/USER_AGENT( 3120): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US,
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1017): InactiveState{ what=131204 }
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
,D/[0]UMC:AdminManager( 3120): init - start
,I/DIAGMON_AGENT( 3139): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED
W/bt-l2cap( 2706): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2706): HC lib lpm enable=0 return 0
W/bt-l2cap( 2706): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2706): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2706): ag scb idx 1 not allocated
W/bt-btif ( 2706): ag scb idx 2 not allocated
E/bt-btif ( 2706): BTA AG is already disabled, ignoring ...
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling,
I/bt_userial_mct( 2706): exiting userial_read_thread
D/bt_userial_mct( 2706): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2706): userial_close_reader Joined userial reader thread: 0
,I/bt_vendor( 2706): hw_epilog_process
D/bt_userial_mct( 2706): userial_close
I/bt_vendor( 2706): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
I/DIAGMON_AGENT( 3139): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1459): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/DIAGMON_AGENT( 3139): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DIAGMON_AGENT( 3139): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3139): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,D/WifiScanningService( 1017): SCAN_AVAILABLE : 1
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiScanningService( 1017): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 1017): SCAN_AVAILABLE : 1
D/RttService( 1017): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/DIAGMON_AGENT( 3139): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WifiP2pService( 1017): P2pDisablingState
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1017): disconnect
D/WifiDisplayController( 1017): updateConnection
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/WifiP2pService( 1017): p2p socket connection lost
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 5ms
D/StatusBar.NetworkController( 1180): EthernetConnected: false
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
,D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/WifiP2pService( 1017): P2pDisabledState
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/WifiP2pService( 1017): DefaultState{ what=143375 }
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AllShareCastTile( 1180): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
E/BluetoothHeadset( 2959): BTStateChangeCB is registed
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/BluetoothHeadset( 2959): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
D/AllShareCastTile( 1180): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3171): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityManager.CallbackHandler( 2067): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
,D/[0]UMC:AdminManager( 3120): loadAdmins
,I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2419:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/ActivityManager( 1017): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2959): BluetoothHeadset service is binded,
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/CommandListener(  277): Clearing all IP addresses on wlan0
,I/libpersona( 3207): KNOX_SDCARD checking this for 1000
D/BluetoothA2dp( 2959): doBind(): CallingUid(myUserHandle) = 0
I/libpersona( 3207): KNOX_SDCARD not a persona
E/Zygote  ( 3207): MountEmulatedStorage()
E/Zygote  ( 3207): v2
,I/SELinux ( 3207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/[0]UMC:AdminManager( 3120): init - end
E/SELinux ( 3207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/GSLBManager( 3120): migrateStoredUrlFromOldPref
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
I/wpa_supplicant( 2037): p2p0: State: DISCONNECTED -> DISCONNECTED
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/AndroidRuntime( 3169): 
D/AndroidRuntime( 3169): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/GSLBManager( 3120): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 3120): deactivateUMCAdminIfNotRequired : -1
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/AndroidRuntime( 3169): CheckJNI is OFF
D/AndroidRuntime( 3169): readGMSProperty: start
D/AndroidRuntime( 3169): readGMSProperty: already setted!!
D/AndroidRuntime( 3169): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3169): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3169): readGMSProperty: end
D/AndroidRuntime( 3169): addProductProperty: start
,D/TimaKeyStoreProvider( 3207): TimaSignature is unavailable
,E/[0]UMC:Utils( 3120): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 3120): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3120): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3120): isContainer : 0
D/ActivityThread( 3207): Added TimaKeyStore provider
I/wpa_supplicant( 2037): Blacklist: Clear (all) 
I/wpa_supplicant( 2037): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged p2p0, false,
D/Tethering( 1017): interfaceStatusChanged p2p0, false
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 3120): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 3120): isContainer : 0
,D/STATUSBAR-WifiQuickSettingButton( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1180): onStateChanged: Wi-Fi
D/STATUSBAR-WifiQuickSettingButton( 1180): Wifi onReceive(0)
,D/HotspotTile( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1180): onReceive : 0, 0
,D/[0]UMC:UMCAdmin( 3120): deactivateUMCAdmin - UMC App Admin deactivated
D/WifiCredService( 1318): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/bt_vendor( 2706): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2706): bluetooth satus is on
I/bt_vendor( 2706): bt-vendor : resetting BT status
I/bt_vendor( 2706): Starting hciattach daemon
I/bt_vendor( 2706): try to set false
,I/bt_vendor( 2706): Starting hciattach daemon
I/bt_vendor( 2706): try to set false
,I/bt_vendor( 2706): cleanup
,I/GKI_LINUX( 2706): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2706): GKI_exit_task 0 done
I/GKI_LINUX( 2706): GKI_shutdown(): task [BTU] terminated
,E/Zygote  ( 3224): MountEmulatedStorage()
I/libpersona( 3224): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3224): v2,
I/libpersona( 3224): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3224 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 2037): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/FOTA    ( 3171): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
I/wpa_supplicant( 2037): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2037): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2037): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/ActivityManager( 1017): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,E/Tethering( 1017): No numeric data
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/BluetoothAdapterState( 2706): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2706): isSecureModeOn:false
D/BluetoothAdapterService( 2706): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.gatt.GattService
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/[0]UMC:GuardService( 3120): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
W/ResourcesManager( 3207): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/[0]UMC:CoreReceiver( 3120): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 3120):  check PreETag 
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2706): handleDebugAction() action=null
,D/BtGatt.GattService( 2706): Received stop request...Stopping profile...
D/BtGatt.GattService( 2706): stop()
D/BtGatt.AdvertiseManager( 2706): advertise clients cleared
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/Tethering( 1017): clearTetheredNotification()
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2419/cgroup.procs: No such file or directory
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1180): updateTetherState():false, false
V/NetworkStats( 1017): performPollLocked() took 6ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 3224): TimaSignature is unavailable
D/ActivityThread( 3224): Added TimaKeyStore provider
,D/HeadsetService( 2706): Received stop request...Stopping profile...
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.hid.HidService
D/[0]UMC:CoreReceiver( 3120): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 3120): Enter loadList
D/[0]UMC:CoreReceiver( 3120): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 3120): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 3120): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 3120): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox,
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,I/wpa_supplicant( 2037): Blacklist: Clear (all) 
,D/[0]UMC:UMCAdmin( 3120): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3120): isContainer : 0
,D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 3120): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 3120): isContainer : 0
,D/[0]UMC:UMCAdmin( 3120): deactivateUMCAdmin - UMC App Admin deactivated
,W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.hdp.HealthService
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2706): Not skipping com.android.bluetooth.map.BluetoothMapService
E/AffinityControl( 3169): AffinityControl: registerfunction enter
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,W/BluetoothAdapterService( 2706): Not skipping com.broadcom.bt.service.sap.SapService
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/libpersona( 3251): KNOX_SDCARD checking this for 10086
I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
I/libpersona( 3251): KNOX_SDCARD not a persona
E/Zygote  ( 3251): MountEmulatedStorage()
E/Zygote  ( 3251): v2
I/SELinux ( 3251): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/[0]UMC:ByodSetupStarter( 3120): Container ID : 0
I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3251 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3251): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/AndroidRuntime( 3169): Calling main entry com.android.commands.pm.Pm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
E/SELinux ( 3251): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2706): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2706): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2706): Stopping profile services that were post enabled
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/BluetoothA2dp( 2959): Proxy object connected
,I/ActivityManager( 1017): Killing 2315:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/A2dpService( 2706): Received stop request...Stopping profile...
D/A2dpStateMachine( 2706): Exit Disconnected: -1
,D/PackageManager( 1017): START PACKAGE DELETE: observer{345818858}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
D/BluetoothA2dp( 1017): Proxy object disconnected
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 2
,E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2706): Profile still running: com.android.bluetooth.hid.HidService
,D/HidService( 2706): Received stop request...Stopping profile...
D/HidService( 2706): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2706): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2706): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2706): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/TimaKeyStoreProvider( 3251): TimaSignature is unavailable
D/ActivityThread( 3251): Added TimaKeyStore provider
W/BluetoothHeadsetServiceJni( 2706): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2706): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2706): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
V/[0]UMC:Utils( 3120): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 3120): shutdown
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/PanService( 2706): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
D/BluetoothMapService( 2706): Received stop request...Stopping profile...
D/BluetoothPan( 1017): BluetoothPAN Proxy object disconnected
D/[0]UMC:GuardService( 3120): @GuardService - stopService Result = true
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
,D/BluetoothA2dp( 2959): Proxy object disconnected
,D/SapService( 2706): Received stop request...Stopping profile...
D/SapService( 2706): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2706): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44bdfbc
I/wpa_supplicant( 2037): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2706): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2706): Proxy object disconnected
D/BluetoothAdapterService( 2706): Bluetooth A2dp source service disconnected
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2706): Profile still running: com.android.bluetooth.map.BluetoothMapService
I/GKI_LINUX( 2706): gki_task task_id=2 [A2DP-MEDIA] terminating
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
I/GKI_LINUX( 2706): GKI_exit_task 2 done
I/GKI_LINUX( 2706): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/BluetoothAdapterService( 2706): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
W/BluetoothHealthServiceJni( 2706): Cleaning up Bluetooth Health Interface...
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
W/BluetoothHealthServiceJni( 2706): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2706): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2706): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2706): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2706): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2706): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(72081340)( 2706): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2706): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2706): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
I/art     ( 3120): System.exit called, status: 0
I/AndroidRuntime( 3120): VM exiting with result code 0, cleanup skipped.
,D/PackageManager( 1017): !@killApplicatoin: 10177, uninstall pkg
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 30
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/PackageSettings( 1017): Skipping PackageSetting{3e14c1cc com.test.thalitest/10175} due to missing metadata
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/BluetoothAdapterState( 2706): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
D/BluetoothAdapterProperties( 2706): Setting state to 10
I/BluetoothAdapterState( 2706): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2706): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2706): updateAdapterState state is 10
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2315/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 2706): Autoconnection is available 
D/BluetoothAdapterService( 2706): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2706): Entering OffState
,D/BluetoothAdapter( 1434): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1434): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2706): onBluetoothStateChange: up=false
I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3120)(adj 0) has died(259,1004)
,D/BluetoothAdapter( 2706): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2959): onBluetoothStateChange: up=false
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10177 user=0: pkg removed
,I/ActivityManager( 1017): Killing 2437:com.example.hello/u0a177 (adj 0): stop com.example.hello cause pkg removed
,W/ActivityManager( 1017): Force removing ActivityRecord{36122476 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 2437
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,E/USB_UICC(  295): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  295): usb_uicc_init_qmi failed ! 
I/USB_UICC(  295): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  295): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/Launcher( 1481): onRestart, Launcher: 164969384
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,V/AlarmManager( 1017): waitForAlarm result :8
I/ActivityManager( 1017): Force stopping com.example.hello appid=10177 user=-1: uninstall pkg
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3171): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,E/SamsungIME( 1815): mOCRHelper is null
,W/GeofencerStateMachine( 1846): Ignoring removeGeofence because network location is disabled.
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1180): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Wi-Fi
,D/HotspotTile( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1318): Action received :android.net.wifi.WIFI_STATE_CHANGED
W/Settings( 1846): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HotspotTile( 1180): onReceive : 1, 0
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,D/BluetoothAdapter( 1446): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1446): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2959): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2959): Bluetooth is turned off, stop adv and scan
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1017): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1304): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
D/comsamsunglog( 1304): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/Launcher( 1481): onStart, Launcher: 164969384
D/Launcher.HomeView( 1481): onStart
,D/Launcher( 1481): onResume, Launcher: 164969384
D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/BluetoothAdapter( 1180): onBluetoothStateChange: up=false
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/BluetoothAdapter( 1180): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1846): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1846): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1459): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1459): Bluetooth is turned off, stop adv and scan
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1481): onResume
,E/BluetoothManagerService( 1017): Unable to call onBluetoothStateChange() on callback #10
E/BluetoothManagerService( 1017): android.os.DeadObjectException
E/BluetoothManagerService( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothManagerService( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothManagerService( 1017): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1067)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2021)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
E/BluetoothManagerService( 1017): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
E/BluetoothManagerService( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService( 1017): 	at android.os.Looper.loop(Looper.java:145)
E/BluetoothManagerService( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothManagerService( 1017): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10162
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,E/UpdateRequestReceiver( 3251): ignoring update request
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3171): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3171): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,D/RegisteredComponentCache( 1446): Collect Tech packages for Knox
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Killing 1563:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_POLICYDM( 3224): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3171): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3171): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
E/Zygote  ( 3290): MountEmulatedStorage()
I/libpersona( 3290): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3290): v2
I/libpersona( 3290): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 3224): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
I/SELinux ( 3290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3290): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3224): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3290 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3171): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3171): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 3171): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,I/DBG_POLICYDM( 3224): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/TimaKeyStoreProvider( 3290): TimaSignature is unavailable
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1304): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/ActivityThread( 3290): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 2507:com.wsomacp/u0a25 (adj 15): empty #31
,D/MenuAppsGridFragment( 1481): onResume
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1017): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,E/Tethering( 1017): No numeric data
,D/PersonaManager( 1446): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3171): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,E/daemonapp( 1304): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1452528592277
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1452550140000
D/daemonapp( 1304): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1304): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,E/Tethering( 1017): No numeric data
,I/DBG_POLICYDM( 3224): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3224): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,E/Tethering( 1017): No numeric data
,D/BluetoothA2dp( 1017): onBluetoothStateChange: up=false
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,I/DBG_POLICYDM( 3224): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/Tethering( 1017): No numeric data
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1017): handle home activity for 0
,I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1452550140000
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/InputDispatcher( 1017): Focus entered window: 1481
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 22
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1452550140000
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/OverheatReceiver( 1180): isSafeMode = false
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/UpdateRequestReceiver( 3251): ignoring update request
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,I/DBG_DM  ( 3171): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 42014(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/40MB, paused 4.744ms total 423.894ms
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/PersonaManager( 1446): isKioskContainerExistOnDevice
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1017): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1017): Bluetooth is turned off, stop adv and scan
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/RegisteredServicesCache( 1446): empty dynamic service
,D/BluetoothA2dp( 2706): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,D/BootupListener( 1459): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceDown() to 8 receivers.
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/PhoneUtilsCommon( 1459): isSupportVoLTE is false.
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/Telecom ( 1434): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1017): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/PackageManager( 1017): delete codoeFile: 
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/GKI_LINUX( 2706): gki_task task_id=1 [BTIF] terminating
,I/DBG_DM  ( 3171): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/GKI_LINUX( 2706): GKI_exit_task 1 done
I/GKI_LINUX( 2706): GKI_shutdown(): task [BTIF] terminated
E/UpdateRequestReceiver( 3251): ignoring update request
,I/BluetoothServiceJni( 2706): cleanupNative: return from cleanup
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10177, packageName = com.example.hello
I/AASA_removePackage( 1017): UID=10177 Target=com.example.hello
,D/ActivityManager( 1017): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,I/SamsungIME( 1815): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothAdapter( 1180): 140440677: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1180): 140440677: getState() :  mService = null. Returning STATE_OFF
,D/comdaemonstockapp( 1304): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1304): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1180):  getBluetoothState : 10
,D/BluetoothAdapter( 1180): 140440677: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1180): 140440677: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1180): 140440677: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PackageManager( 1017): result of delete: 1{345818858}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/art     ( 2706): System.exit called, status: 0
I/AndroidRuntime( 2706): VM exiting with result code 0, cleanup skipped.
,I/DBG_POLICYDM( 3224): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/Tethering( 1017): interfaceRemoved wlan0
,E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
D/BluetoothAdapter( 1846): 1003336285: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1846): 1003336285: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 3169): Shutting down VM
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3224): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
I/Telecom ( 1434): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10177 container id = 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/DBG_POLICYDM( 3224): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/UpdateRequestReceiver( 3251): ignoring update request
,E/Zygote  ( 3334): MountEmulatedStorage(),
E/Zygote  ( 3334): v2
,I/libpersona( 3334): KNOX_SDCARD checking this for 10166
I/ActivityManager( 1017): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3334 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 3334): KNOX_SDCARD not a persona,
,I/SELinux ( 3334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,I/ActivityManager( 1017): Process com.android.bluetooth (pid 2706)(adj 0) has died(334,982)
,I/SELinux ( 3334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/[SBeam] ( 1318): SBeamEnabler.isSBeamSupported : [-1]
,E/SELinux ( 3334): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/Tethering( 1017): interfaceRemoved p2p0
E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10177,
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,I/DBG_DM  ( 3171): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 2437 uid 10177
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1815): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/[SBeam] ( 1318): SBeamEnabler.isSBeamSupported : EXIST
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
W/TextServicesManagerService( 1017): no available spell checker services found
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,I/DBG_DM  ( 3171): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,D/TimaKeyStoreProvider( 3334): TimaSignature is unavailable
E/Tethering( 1017): No numeric data
,D/ActivityThread( 3334): Added TimaKeyStore provider
,I/DBG_DM  ( 3171): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3171): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/Tethering( 1017): No numeric data
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,E/Zygote  ( 3353): MountEmulatedStorage()
E/Zygote  ( 3353): v2
I/libpersona( 3353): KNOX_SDCARD checking this for 10057
I/libpersona( 3353): KNOX_SDCARD not a persona
,I/SELinux ( 3353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3353 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/SELinux ( 3353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3353): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10177
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::,
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,E/UpdateRequestReceiver( 3251): ignoring update request
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1017): [SO] activate (ident=0xb85ce4c0, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=2_task.xml
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
,D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb85ce4c0, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,V/AlarmManagerEXT( 1017): com.example.hello(10177) is removed.
W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1017): [BT Setting State] State =10
I/InputMethodManagerService( 1017): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/TimaKeyStoreProvider( 3353): TimaSignature is unavailable
,E/UpdateRequestReceiver( 3251): ignoring update request
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,D/ActivityThread( 3353): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,W/art     ( 3169): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/Zygote  ( 3378): MountEmulatedStorage()
,E/Zygote  ( 3378): v2
I/libpersona( 3378): KNOX_SDCARD checking this for 10092
I/libpersona( 3378): KNOX_SDCARD not a persona
I/SELinux ( 3378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3378 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3378): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SMD     (  287): DCD OFF
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/audio_hw_primary(  282): adev_get_parameters: enter: keys - call_forwarding
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
D/audio_hw_extn(  282): audio_extn_get_parameters: returns 
V/msm8974_platform(  282): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  282): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  282): key: 'call_forwarding' value: ''
,V/InCall  ( 1950): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1950): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1950): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,I/ActivityManager( 1017): Displayed Component not be shown by security: +899ms
,D/TimaKeyStoreProvider( 3378): TimaSignature is unavailable
,D/ActivityThread( 3378): Added TimaKeyStore provider
,D/ScoverManager( 1950): serviceVersion : 16908288
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1950): InCallUtils - isCoverClosed false
,W/NotificationAccessSettings( 1318): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/Telecom ( 1434): ProximitySensorManager: Proximity wake lock already released
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1950): InCallUtils - isCoverClosed false
,I/InCall  ( 1950): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1950): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1950): InCallPresenter -  - dismissCoverDialog()...
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/InCall  ( 1950): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1950): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PhoneStatusBarView( 1180): setCallBackground:0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1563/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2507/cgroup.procs: No such file or directory
,W/ResourcesManager( 1318): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1950): InCallUtils - isCoverClosed false
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3394): MountEmulatedStorage(),
I/libpersona( 3394): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3394): v2
I/libpersona( 3394): KNOX_SDCARD not a persona
I/SELinux ( 3394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2595:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2562:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
,I/ActivityManager( 1017): Killing 2544:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #33
,D/TimaKeyStoreProvider( 3394): TimaSignature is unavailable
,D/ActivityThread( 3394): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_2562/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_2544/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2595/cgroup.procs: No such file or directory
,D/SensorService( 1017): [SO] currT = 38160070348, prevT = 37720078005, diff = 439992343, [0.057 0.153 10.113]
,D/VideoCallManager( 1950): Instantiating VideoCallManager
D/SensorService( 1017): [SO] 0.057 0.153 10.113
,D/SensorService( 1017): [SO] [100 -> 255]
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1950): took 2.136615ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1950): took 5.236042ms for 0*0 texture 0
,I/GFX raster( 1950): took 11.202971ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb81fe678 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8216888 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/DBG_FMMDM( 3394): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/Adreno-EGL( 1950): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1950): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1950): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1950): Local Branch: 
I/Adreno-EGL( 1950): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1950): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1950):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DBG_FMMDM( 3394): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3394): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3394): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,I/GFX GPU raster( 1950): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1950): took 0.315729ms for 320*61440 texture 37809
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/draw setup( 1950): took 10.721563ms for 320*240 texture 37809
E/GFX GPU raster( 1950): drawn
,I/Choreographer( 1481): Skipped 35 frames!  The application may be doing too much work on its main thread.
I/GFX GPU raster ASTC( 1950): took 42.027812ms for 320*240 texture 12
I/GFX raster( 1950): took 42.094010ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb8216888 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8218bc8 counterpartCT=4 counterpartW=320 counterparth=240
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/libpersona( 3416): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3416): MountEmulatedStorage()
I/libpersona( 3416): KNOX_SDCARD not a persona
E/Zygote  ( 3416): v2
I/SELinux ( 3416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3416): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3416 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/LocationManagerService( 1017): getProviders()=[passive]
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1950): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1950): took 0.341562ms for 480*122880 texture 37813
I/draw setup( 1950): took 0.699844ms for 480*640 texture 37813
E/GFX GPU raster( 1950): drawn
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/GFX GPU raster ASTC( 1950): took 7.172239ms for 480*640 texture 12
I/GFX raster( 1950): took 7.254895ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb8218bc8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8447058 counterpartCT=4 counterpartW=480 counterparth=640
,I/art     (  302): Explicit concurrent mark sweep GC freed 8727(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 28.842ms
,I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@c72a47e time:38276
,D/TimaKeyStoreProvider( 3416): TimaSignature is unavailable
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
D/ActivityThread( 3416): Added TimaKeyStore provider
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 24.884ms
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1950): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1950): took 0.358750ms for 440*116864 texture 37809,
I/draw setup( 1950): took 0.947292ms for 440*330 texture 37809
E/GFX GPU raster( 1950): drawn
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 670us total 17.379ms
,I/GFX GPU raster ASTC( 1950): took 4.775781ms for 440*330 texture 12
I/GFX raster( 1950): took 4.851145ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb8447058 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb845b448 counterpartCT=4 counterpartW=440 counterparth=330
,E/Zygote  ( 3435): MountEmulatedStorage()
E/Zygote  ( 3435): v2
I/libpersona( 3435): KNOX_SDCARD checking this for 1000
I/libpersona( 3435): KNOX_SDCARD not a persona
,I/SELinux ( 3435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{163120e8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:38341
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1950): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1950): took 0.606407ms for 480*163840 texture 37811
I/draw setup( 1950): took 0.998125ms for 480*640 texture 37811
E/GFX GPU raster( 1950): drawn
,I/GFX GPU raster ASTC( 1950): took 6.491198ms for 480*640 texture 12
I/GFX raster( 1950): took 6.581822ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb844b258 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb845af80 counterpartCT=4 counterpartW=480 counterparth=640
,D/TimaKeyStoreProvider( 3435): TimaSignature is unavailable
,D/ActivityThread( 3435): Added TimaKeyStore provider
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 3334): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3334): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ScoverManager( 1318): serviceVersion : 16908288
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1950): took 2.136094ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1950): took 7.485417ms for 0*0 texture 0
,I/GFX raster( 1950): took 11.594739ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb8444918 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8444a38 counterpartCT=4 counterpartW=176 counterparth=144
,I/PCWCLIENTTRACE_LOG( 3435): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3435): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3435): new DMDBOpenHelper instance
,E/        ( 1950): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1950): took 2.127240ms for 0*0 texture 0
I/ActivityManager( 1017): Killing 2645:com.android.calendar/u0a135 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2628:com.samsung.android.securitylogagent/1000 (adj 15): empty #32
,I/GFX generate_partition_tables( 1950): took 6.241145ms for 0*0 texture 0
,I/GFX raster( 1950): took 10.537030ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1950): Bitmap=0xb8444c58 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8444bf8 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1950): registerListener
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@251befe6, pid : 1950, uid : 1001, type : 1
,D/InCall  ( 1950): InCallPresenter -  - Finished InCallPresenter.setUp
,V/JNIHelp ( 3334): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PCWCLIENTTRACE_DMContentProvider( 3435): [URIMatcher] - result : 2
,I/DBG_FMMDM( 3394): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3394): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3394): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3458): MountEmulatedStorage()
,E/Zygote  ( 3458): v2
I/libpersona( 3458): KNOX_SDCARD checking this for 1000
I/SELinux ( 3458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3458): KNOX_SDCARD not a persona
I/SELinux ( 3458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3458 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3458): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2530:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2722:com.android.keychain/1000 (adj 15): empty #32
,D/TimaKeyStoreProvider( 3458): TimaSignature is unavailable
,D/ActivityThread( 3458): Added TimaKeyStore provider
,W/ActivityThread( 3334): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3334): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@318920e4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3334): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1017): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,E/Zygote  ( 3473): MountEmulatedStorage()
E/Zygote  ( 3473): v2
I/libpersona( 3473): KNOX_SDCARD checking this for 10092
I/libpersona( 3473): KNOX_SDCARD not a persona
,I/SELinux ( 3473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3473 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_FMMDS( 3458): [50.18.150420][Line:56][onCreate] FMMDS Application Start
I/SELinux ( 3473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3473): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2645/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2628/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2722/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_2530/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3473): TimaSignature is unavailable
,D/ActivityThread( 3473): Added TimaKeyStore provider
,I/DBG_FMMDS( 3458): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/PCWCLIENTTRACE_DMContentProvider( 3435): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3458): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3458): [50.18.150420][Line:43][xdbDBInit] 
,I/LockPatternUtils( 1318): isSmartCardAuthenticationAvailable: false
,I/DBG_DM  ( 3171): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,D/Settings_Utils( 1318): isSupportVNFestival SM-A500FU XEO
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3378): Setting receiver enabled: false
,E/ActivityThread( 3378): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/DBG_FMMDS( 3458): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/DBG_FMMDS( 3458): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3458): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3458): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3458): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3458): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3458): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,I/dbxyzptlk.db240408.D.h( 3378): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/dbxyzptlk.db240408.D.h( 3378): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/FOTA_Client( 3290): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/dbxyzptlk.db240408.D.h( 3378): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/FOTA_Client( 3290): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3290): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,I/dbxyzptlk.db240408.D.h( 3378): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,W/FOTA_Client( 3290): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3501): MountEmulatedStorage()
,E/Zygote  ( 3501): v2
I/libpersona( 3501): KNOX_SDCARD checking this for 10014
I/libpersona( 3501): KNOX_SDCARD not a persona
,I/SELinux ( 3501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3501 uid=10014 gids={50014, 9997} abi=armeabi-v7a,
E/SELinux ( 3501): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2807:com.android.email/u0a145 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3501): TimaSignature is unavailable
,D/ActivityThread( 3501): Added TimaKeyStore provider
,D/breakpad( 3378): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,W/ResourcesManager( 3334): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3334): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/OneTimeInitializerReceiver( 3501): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3501): OneTimeService.onHandleIntent
,I/FactoryTestApp( 2682): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3158)  
,I/com.dropbox.sync.android.a( 3378): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ActivityManager( 1017): Killing 1771:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3529): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3529 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3529): v2
I/libpersona( 3529): KNOX_SDCARD checking this for 1000
I/SELinux ( 3529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3529): KNOX_SDCARD not a persona
I/SELinux ( 3529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3529): TimaSignature is unavailable
,D/ActivityThread( 3529): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10145/pid_2807/cgroup.procs: No such file or directory
,I/dex2oat ( 3539): ----------------------------------------------------
I/dex2oat ( 3539): <SS>: S T A R T I N G . . .
I/dex2oat ( 3539): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3539): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1024812724.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1024812724.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/com.dropbox.sync.android.ad( 3378): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3529): onCreate
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3549): MountEmulatedStorage()
I/libpersona( 3549): KNOX_SDCARD checking this for 10019
E/Zygote  ( 3549): v2
I/libpersona( 3549): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3549 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 3549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/libprocessgroup( 1017): failed to open /acct/uid_10004/pid_1771/cgroup.procs: No such file or directory
I/SELinux ( 3549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/LockPatternUtils( 1318): isSmartCardAuthenticationAvailable: false
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 3549): TimaSignature is unavailable
,D/ActivityThread( 3549): Added TimaKeyStore provider
,I/Hs20UtilService( 3529): Starting #1
,I/Hs20UtilService( 3529): Message received 5003
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3572): MountEmulatedStorage()
,E/Zygote  ( 3572): v2
I/libpersona( 3572): KNOX_SDCARD checking this for 10003
I/libpersona( 3572): KNOX_SDCARD not a persona
,I/SELinux ( 3572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3572 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/dbxyzptlk.db240408.A.l( 3378): flushLog
I/dbxyzptlk.db240408.A.l( 3378): java.io.IOException: write failed: EBADF (Bad file number)
I/dbxyzptlk.db240408.A.l( 3378): 	at libcore.io.IoBridge.write(IoBridge.java:502)
I/dbxyzptlk.db240408.A.l( 3378): 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
I/dbxyzptlk.db240408.A.l( 3378): 	at com.dropbox.android.util.K.write(panda.py:83)
I/dbxyzptlk.db240408.A.l( 3378): 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:167)
I/dbxyzptlk.db240408.A.l( 3378): 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:158)
I/dbxyzptlk.db240408.A.l( 3378): 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
I/dbxyzptlk.db240408.A.l( 3378): 	at dbxyzptlk.db240408.A.l.a(panda.py:176)
I/dbxyzptlk.db240408.A.l( 3378): 	at dbxyzptlk.db240408.A.l.a(panda.py:200)
I/dbxyzptlk.db240408.A.l( 3378): 	at dbxyzptlk.db240408.A.l.a(panda.py:136)
I/dbxyzptlk.db240408.A.l( 3378): 	at dbxyzptlk.db240408.A.a.a(panda.py:1994)
I/dbxyzptlk.db240408.A.l( 3378): 	at com.dropbox.android.b.c(panda.py:425)
I/dbxyzptlk.db240408.A.l( 3378): 	at com.dropbox.android.b.<init>(panda.py:275)
I/dbxyzptlk.db240408.A.l( 3378): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.os.Looper.loop(Looper.java:145)
I/dbxyzptlk.db240408.A.l( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
I/dbxyzptlk.db240408.A.l( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
I/dbxyzptlk.db240408.A.l( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
I/dbxyzptlk.db240408.A.l( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
I/dbxyzptlk.db240408.A.l( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/dbxyzptlk.db240408.A.l( 3378): Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
I/dbxyzptlk.db240408.A.l( 3378): 	at libcore.io.Posix.writeBytes(Native Method)
I/dbxyzptlk.db240408.A.l( 3378): 	at libcore.io.Posix.write(Posix.java:223)
I/dbxyzptlk.db240408.A.l( 3378): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
I/dbxyzptlk.db240408.A.l( 3378): 	at libcore.io.IoBridge.write(IoBridge.java:497)
I/dbxyzptlk.db240408.A.l( 3378): 	... 23 more
,I/RlzPingService( 3416): Setting next ping for 1453133394314
,E/dex2oat ( 3539): Failed to seek to oat code section. Actual: 16332 Expected: 475 File: /data/data/com.google.android.youtube/cache/ads1024812724.dex: Bad file number
E/dex2oat ( 3539): Failed to write oat code to /data/data/com.google.android.youtube/cache/ads1024812724.dex
E/dex2oat ( 3539): Failed to write .rodata and .text for /data/data/com.google.android.youtube/cache/ads1024812724.dex: Bad file number
E/dex2oat ( 3539): Unable to write to file /data/data/com.google.android.youtube/cache/ads1024812724.dex
E/dex2oat ( 3539): Failed to write ELF file /data/data/com.google.android.youtube/cache/ads1024812724.dex
E/dex2oat ( 3539): Failed to create oat file: /data/data/com.google.android.youtube/cache/ads1024812724.dex
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3572): TimaSignature is unavailable
,D/ActivityThread( 3572): Added TimaKeyStore provider
,E/Zygote  ( 3591): MountEmulatedStorage()
E/Zygote  ( 3591): v2
I/libpersona( 3591): KNOX_SDCARD checking this for 10094
I/libpersona( 3591): KNOX_SDCARD not a persona
,I/SELinux ( 3591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3591): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3591 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2790:com.samsung.android.sm/1000 (adj 15): empty #31
,W/FileUtils( 2663): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,I/ActivityManager( 1017): Killing 2864:flipboard.boxer.app/u0a99 (adj 15): empty #31
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/TimaKeyStoreProvider( 3591): TimaSignature is unavailable
,D/ActivityThread( 3591): Added TimaKeyStore provider
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,W/System.err( 3334): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 3179): (28) failed to open "/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3179): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 3179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLit,eDatabase( 3179): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3179): 	at com.sec.providers.settingsearch.SettingSearchProvider.addSearchInfoDB(SettingSearchProvider.java:950)
E/SQLiteDatabase( 3179): 	at com.sec.providers.settingsearch.SettingSearchProvider.call(SettingSearchProvider.java:893)
E/SQLiteDatabase( 3179): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:382)
E/SQLiteDatabase( 3179): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/SQLiteDatabase( 3179): 	at android.os.Binder.execTransact(Binder.java:461)
E/DatabaseUtils( 3179): Writing exception to parcel
E/DatabaseUtils( 3179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/DatabaseUtils( 3179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/DatabaseUtils( 3179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 3179): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 3179): 	at com.sec.providers.settingsearch.SettingSearchProvider.addSearchInfoDB(SettingSearchProvider.java:950)
E/DatabaseUtils( 3179): 	at com.sec.providers.settingsearch.SettingSearchProvider.call(SettingSearchProvider.java:893)
E/DatabaseUtils( 3179): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:382)
E/DatabaseUtils( 3179): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3179): 	at android.os.Binder.execTransact(Binder.java:461)
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2790/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_2864/cgroup.procs: No such file or directory
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,D/UserAnalysis.PlaceProvider( 3572): PlaceProvider onCreate()
D/elm:15183( 3591): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
E/AndroidRuntime( 1318): FATAL EXCEPTION: Thread-59
E/AndroidRuntime( 1318): Process: com.android.settings, PID: 1318
E/AndroidRuntime( 1318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1318): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
E/AndroidRuntime( 1318): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 1318): 	at android.content.ContentProviderProxy.call(ContentProviderNative.java:643)
E/AndroidRuntime( 1318): 	at android.content.ContentResolver.call(ContentResolver.java:1425)
E/AndroidRuntime( 1318): 	at com.android.settings.settingssearch.SettingsSearchManager.addSearchInfoDB(SettingsSearchManager.java:181)
E/AndroidRuntime( 1318): 	at com.android.settings.settingssearch.SettingsSearchUtils.initSearchDB(SettingsSearchUtils.java:330)
E/AndroidRuntime( 1318): 	at com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run(SettingsSearchIntentReceiver.java:128)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/elm:15183( 3591): ELMEngine.ELMEngine( context ).
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/elm:15183( 3591): MDMBridge.setEnterpriseBridge()
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/ActivityManager( 1017): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/elm:15183( 3591): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
D/elm:15183( 3591): ElmAgentService : onCreate()
,D/elm:15183( 3591): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/System.out( 3378): Thread-444(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/elm:15183( 3591): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3591): BootCompletedState : startBootCompleted() call
I/KLMS-2.5.183: ( 3549): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 17:09:54 GMT+01:00 2016
I/System.out( 3378): Thread-444(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3378): Thread-444(ApacheHTTPLog):isShipBuild true
I/System.out( 3378): Thread-444(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3378): Thread-444(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 1017): *FMB* installDecor flags : 8519682
D/EnterpriseController(  277): uids 10092
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10092
E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1017): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1017): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1017): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15989)
E/DropBoxManagerService( 1017): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1017): 	... 5 more
,E/android.os.Debug( 1017): ro.product_ship = true
E/android.os.Debug( 1017): ro.debug_level = 0x4f4c
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(Co,ntextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/da,tabases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
D/elm:15183( 3591): MDMBridge.getAllLicenseInfoFromSDK()
I/elm:15183( 3591): Get License : 0
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
I/System.out( 3378): pool-10-thread-1 calls detatch()
E/SQLiteDatabase( 2663): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2663): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2663): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2663): 	at java.lang.Thread.run(Thread.java:818)
D/UserAnalysis.SecureDbManager( 3572): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 3572): SecurePlaceDbHelper() 
D/UserAnalysis( 3572): Create SecureDbHelper
D/InputDispatcher( 1017): Focus left window: 1481
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher( 1017): Focus entered window: 1017
D/ActivityManager( 1017): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/SQLiteLog( 2663): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/elm:15183( 3591): ElmAgentService : onDestroy().
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent

```
