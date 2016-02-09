#### Test 584164489c56086_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
W/ActivityManager(  897): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 6206): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager(  897): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,--------- beginning of main
I/Gmail   ( 6206): getAccountsCursor
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6206): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  897): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  897): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  897): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6206): Observing account changes for notifications
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_in.png
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
W/ActivityManager(  897): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  897): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6206): Error finding the version of the Email provider.....
E/Gmail   ( 6206): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6206): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 6206): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 6206): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 6206): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6206): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6206): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6206): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6206): We do not support migrating this version of the Email provider.
I/Gmail   ( 6206): getAccountsCursor
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  897): Killing 4745:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
I/SettingSearchManagerReceiver( 1477): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1477): addSearchInfoDB
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Zygote  ( 6254): MountEmulatedStorage()
I/libpersona( 6254): KNOX_SDCARD checking this for 10168
E/Zygote  ( 6254): v2
I/libpersona( 6254): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6254 uid=10168 gids={50168, 9997} abi=armeabi-v7a
I/SELinux ( 6254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  897): failed to open /acct/uid_10138/pid_4745/cgroup.procs: No such file or directory
I/SELinux ( 6254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6254): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6254): TimaSignature is unavailable
D/ActivityThread( 6254): Added TimaKeyStore provider
D/ResourcesManager( 6254): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
D/AndroidRuntime( 6249): 
D/AndroidRuntime( 6249): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/SQLiteLog( 6206): (283) recovered 665 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/AndroidRuntime( 6249): CheckJNI is OFF
D/AndroidRuntime( 6249): setted country_code = Germany
D/AndroidRuntime( 6249): setted countryiso_code = DE
D/AndroidRuntime( 6249): setted sales_code = DBT
D/AndroidRuntime( 6249): readGMSProperty: start
D/AndroidRuntime( 6249): readGMSProperty: already setted!!
D/AndroidRuntime( 6249): readGMSProperty: end
D/AndroidRuntime( 6249): addProductProperty: start
D/ResourcesManager( 2365): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/SMD     (  286): DCD ON
E/File    ( 6206): fail readDirectory() errno=2
I/Gmail   ( 6206): notifyAccountChanged
I/Gmail   ( 6206): getAccountsCursor
I/Gmail   ( 6206): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6206): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6206): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6206): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/SettingSearchManagerReceiver( 1477): endInsert
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6281): MountEmulatedStorage()
E/Zygote  ( 6281): v2
I/libpersona( 6281): KNOX_SDCARD checking this for 1000
I/libpersona( 6281): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=6281 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/AffinityControl( 6249): AffinityControl: registerfunction enter
I/SELinux ( 6281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  897): Killing 5193:com.android.email/u0a163 (adj 15): bgCount ##41
I/SELinux ( 6281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6281): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6249): Calling main entry com.android.commands.am.Am
I/Gmail   ( 6206): getAccountsCursor
E/PersonaManagerService(  897): inState():  stateMachine is null !!
I/ActivityManager(  897): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/TimaKeyStoreProvider( 6281): TimaSignature is unavailable
D/ActivityThread( 6281): Added TimaKeyStore provider
D/AndroidRuntime( 6249): Shutting down VM
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 6281): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/AssistantMenuSettingSearch( 6281): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 6281): Make Setting DB
W/libprocessgroup(  897): failed to open /acct/uid_10163/pid_5193/cgroup.procs: No such file or directory
W/ContextImpl( 6281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6303): MountEmulatedStorage()
E/Zygote  ( 6303): v2
I/libpersona( 6303): KNOX_SDCARD checking this for 10117
I/libpersona( 6303): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6303 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6303): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6303): TimaSignature is unavailable
D/ActivityThread( 6303): Added TimaKeyStore provider
D/ResourcesManager( 6303): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager( 6303): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/NotifUtils( 6206): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
I/NotifUtils( 6206): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
I/NotifUtils( 6206): Showing notification with unreadCount of 7 and unseenCount of 7
I/PeopleDatabaseHelper( 2365): cleanUpNonGplusAccounts done.
I/Babel   ( 6303): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6303): MmsConfig.loadMmsSettings
I/Babel   ( 6303): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 6303): MmsConfig.loadFromDatabase
D/ResourcesManager( 6303): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
E/Babel   ( 6303): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6303): MmsConfig.loadFromResources
W/AudioCapabilities( 6303): Unsupported mime audio/evrc
E/Babel   ( 6303): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6303): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
W/AudioCapabilities( 6303): Unsupported mime audio/qcelp
W/VideoCapabilities( 6303): Unrecognized profile 2130706433 for video/avc
W/Settings( 6303): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6303): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 6303): Unsupported mime audio/mpeg-L2
W/AudioCapabilities( 6303): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6303): Unsupported mime audio/x-ima
W/AudioCapabilities( 6303): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6303): Unsupported mime audio/qcelp
W/AudioCapabilities( 6303): Unsupported mime audio/evrc
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
W/VideoCapabilities( 6303): Unsupported mime video/wvc1
W/VideoCapabilities( 6303): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6303): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6303): Unsupported mime video/wvc1
W/VideoCapabilities( 6303): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6303): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 6303): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 6303): Unsupported mime video/mp43
W/VideoCapabilities( 6303): Unsupported mime video/sorenson
I/VideoCapabilities( 6303): Unsupported profile 4 for video/mp4v-es
E/SQLiteLog( 6303): (284) automatic index on conversation_participants_view(conversation_id)
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
E/SQLiteLog( 6303): (284) automatic index on conversation_participants_view(conversation_id)
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
E/SQLiteLog( 6303): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 6303): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 6303): (284) automatic index on conversation_participants_view(conversation_id)
D/GCM     ( 1674): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/ActivityManager(  897): Killing 5673:com.samsung.android.service.travel/u0a178 (adj 15): bgCount ##41
V/GmsCoreStatsServiceLauncher( 2365): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 2069): [232] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2365): Restart initialization of location
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
W/libprocessgroup(  897): failed to open /acct/uid_10178/pid_5673/cgroup.procs: No such file or directory
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/GCM     ( 1674): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/AuthorizationBluetoothService( 1674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2365): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 2069): [225] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2365): Restart initialization of location
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
V/BitmapFactory( 6206): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NotifUtils( 6206): Account: 61035162 vibrate: false
,I/NotifUtils( 6206): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|1729800001|null|10114
,D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
,V/AudioPolicyManager(  291): getOutputsForDevice device 0002 -> 0002
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
I/AudioService(  897): getStreamVolume 5 index 110
D/LightsService(  897): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
D/LightsService(  897): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ResourcesManager( 1169): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1762): (284) automatic index on sqlite_sq_AFA26F10(STAT_DATA_ID)
,V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-913293406|null|10114
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,I/ValidateNoPeople(  897): final affinity: 0.0
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-865450363|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@e0345bd
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,I/ValidateNoPeople(  897): final affinity: 0.0
,I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|-913293406|null|10114
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-633420634|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|438982678|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/GCM     ( 1674): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,D/ResourcesManager( 6303): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|1919793178|null|10114
,I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2365): [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,I/ValidateNoPeople(  897): final affinity: 0.0
,D/ResourcesManager( 6303): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/ResourcesManager( 6303): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|2046740944|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,V/JNIHelp ( 6303): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityThread( 6303): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthServiceInstalled() : HealthService is Installed.
W/System  ( 6303): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c66aac6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6303): Installed default security provider GmsCore_OpenSSL
D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 2365): Explicit concurrent mark sweep GC freed 17330(1266KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 19MB/32MB, paused 776us total 45.504ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 6303): UserRecoverableAuthException.
,E/Babel   ( 6303): cfq: BadAuthentication
E/Babel   ( 6303): 	at cfn.a(Unknown Source)
E/Babel   ( 6303): 	at f.a(PG:191)
E/Babel   ( 6303): 	at ava.a(PG:88)
E/Babel   ( 6303): 	at ava.a(PG:128)
E/Babel   ( 6303): 	at bjs.a(PG:255)
E/Babel   ( 6303): 	at bep.a(PG:602)
E/Babel   ( 6303): 	at bep.a(PG:469)
E/Babel   ( 6303): 	at bpo.run(PG:1141)
E/Babel   ( 6303): Error getting auth token
E/Babel   ( 6303): bxl
E/Babel   ( 6303): 	at f.a(PG:201)
E/Babel   ( 6303): 	at ava.a(PG:88)
E/Babel   ( 6303): 	at ava.a(PG:128)
E/Babel   ( 6303): 	at bjs.a(PG:255)
E/Babel   ( 6303): 	at bep.a(PG:602)
E/Babel   ( 6303): 	at bep.a(PG:469)
E/Babel   ( 6303): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6303): error sending REQ[fc:0; creat:1455009577901; type:bev-949248892]; took 100 ms (error code == 100)
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Babel   ( 6303): Account registration failedRedacted-21
,E/Babel   ( 6303): bph: null -- null
E/Babel   ( 6303): 	at ava.a(PG:120)
E/Babel   ( 6303): 	at ava.a(PG:128)
E/Babel   ( 6303): 	at bjs.a(PG:255)
E/Babel   ( 6303): 	at bep.a(PG:602)
E/Babel   ( 6303): 	at bep.a(PG:469)
E/Babel   ( 6303): 	at bpo.run(PG:1141)
I/Babel   ( 6303): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 6303): Account sign in complete with state 106account: Redacted-21
,I/art     ( 6303): Note: end time exceeds epoch: 
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/Zygote  ( 6368): MountEmulatedStorage()
,E/Zygote  ( 6368): v2
I/libpersona( 6368): KNOX_SDCARD checking this for 10036
I/libpersona( 6368): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6368 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6368): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 1674): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/ic_launcher_babel.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/TimaKeyStoreProvider( 6368): TimaSignature is unavailable
,D/ActivityThread( 6368): Added TimaKeyStore provider
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Babel   ( 6303): Unexpected exception while authenticating.
,E/Babel   ( 6303): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6303): 	at cfn.b(Unknown Source)
E/Babel   ( 6303): 	at cfn.a(Unknown Source)
E/Babel   ( 6303): 	at f.a(PG:188)
E/Babel   ( 6303): 	at ava.b(PG:143)
E/Babel   ( 6303): 	at bnr.run(PG:5415)
E/Babel   ( 6303): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6303): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6303): 	at java.lang.Thread.run(Thread.java:818)
,D/ResourcesManager( 6368): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/ResourcesManager( 6368): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 6368): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6368): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6368): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6368): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6368): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6368): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6368): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
,W/ResourcesManager( 6368): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6368): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,I/art     (  897): Background partial concurrent mark sweep GC freed 336846(20MB) AllocSpace objects, 12(8MB) LOS objects, 27% free, 42MB/58MB, paused 1.883ms total 126.002ms
,E/SPPClientService( 5217): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6399): MountEmulatedStorage()
E/Zygote  ( 6399): v2
I/libpersona( 6399): KNOX_SDCARD checking this for 10038
I/libpersona( 6399): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6399 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6399): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  897): Killing 5696:com.sec.android.app.samsungapps/u0a40 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6399): TimaSignature is unavailable
,D/ActivityThread( 6399): Added TimaKeyStore provider
,D/ResourcesManager( 6399): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6399): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6399): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6399): PushLog.txt file is not deleted.
D/SPPClientService( 6399): PushLog.txt file is not deleted.
D/SPPClientService( 6399): ============PushLog. stop!
,W/libprocessgroup(  897): failed to open /acct/uid_10040/pid_5696/cgroup.procs: No such file or directory
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6418): MountEmulatedStorage()
E/Zygote  ( 6418): v2
I/libpersona( 6418): KNOX_SDCARD checking this for 10038
I/libpersona( 6418): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=6418 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5418:com.sec.android.fotaclient/u0a11 (adj 15): bgCount ##41
,I/SELinux ( 6418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6418): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6418): TimaSignature is unavailable
,D/ActivityThread( 6418): Added TimaKeyStore provider
,D/ResourcesManager( 6418): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10011/pid_5418/cgroup.procs: No such file or directory
,E/SPPClientService( 6418): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6418): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6418): PushLog.txt file is not deleted.
D/SPPClientService( 6418): PushLog.txt file is not deleted.
D/SPPClientService( 6418): ============PushLog. stop!
,E/LNoti   ( 6418): [PhoneStatusChangeReceiver] This device doesn't register yet.
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4700): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,V/BitmapFactory( 4700): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/s_health_widget_engraft_pedometer_mask.qmg
,V/BitmapFactory( 4700): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/s_health_widget_engraft_pedometer_icon.qmg
,V/BitmapFactory( 4700): DecodeImagePath(decodeResourceStream3) : res/drawable-xxxhdpi/s_health_widget_mask.qmg
,V/BitmapFactory( 4700): DecodeImagePath(decodeResourceStream3) : res/drawable-xxxhdpi/s_health_widget_pedometer_icon_02.qmg
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :8
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
W/Search.LoginHelper( 1553): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/PackageManager(  897): verifying app can be installed or not
,D/ApplicationPolicy(  897): isApplicationInstallationEnabled
,D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy(  897): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall(  897): product true
,I/FaceInterface( 6015): startFaceScan() : going on
D/FaceInterface( 6015): startFaceScan() is called.
,D/ContentApp( 1221): startScan() is called.
,D/FaceValue( 1221): mSleepTime: 800
D/FaceValue( 1221): mMaxThreadNum: 2
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1221): isNeedToRestore : start
,I/FaceInterface( 6015): startFaceScan() : going on
,D/FaceInterface( 6015): startFaceScan() is called.
,D/ContentApp( 1221): startScan() is called.
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1221): isNeedToRestore : start
,I/art     ( 1221): Explicit concurrent mark sweep GC freed 5862(355KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 323us total 20.826ms
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6459): MountEmulatedStorage()
E/Zygote  ( 6459): v2
I/libpersona( 6459): KNOX_SDCARD checking this for 10034
I/libpersona( 6459): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6459 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5442:com.samsung.klmsagent/u0a19 (adj 15): bgCount ##41
,I/SELinux ( 6459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6459): TimaSignature is unavailable
,D/ActivityThread( 6459): Added TimaKeyStore provider
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10019/pid_5442/cgroup.procs: No such file or directory
,D/PackageManager(  897): Existing package
,D/PackageManager(  897): Renaming /data/app/vmdl198038039.tmp to /data/app/com.test.thalitest-1
,D/PackageManager(  897): installNewPackageLI: Package{357600b7 com.test.thalitest}
,I/FeatureConfig( 6459): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/art     (  897): Background partial concurrent mark sweep GC freed 69949(3MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 50MB/66MB, paused 1.424ms total 105.080ms
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 6459): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5801): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ActivityManager(  897): Killing 5143:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1553): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6482): MountEmulatedStorage()
I/libpersona( 6482): KNOX_SDCARD checking this for 10075
E/Zygote  ( 6482): v2
I/libpersona( 6482): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6482 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  897): failed to open /acct/uid_10037/pid_5143/cgroup.procs: No such file or directory
E/SELinux ( 6482): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6482): TimaSignature is unavailable
,D/ActivityThread( 6482): Added TimaKeyStore provider
,D/ResourcesManager( 6482): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 18013(999KB) AllocSpace objects, 6(486KB) LOS objects, 39% free, 17MB/29MB, paused 462us total 28.412ms
,D/ResourcesManager( 2365): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/FileShare-Server( 6482): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/SELinux (  294): selinux_android_setcategory: no category for userid: 0, path: /data/data/com.test.thalitest/lib 
,I/art     (  897): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
,I/art     (  897): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
,D/PackageManager(  897): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,E/Zygote  ( 6498): MountEmulatedStorage()
I/libpersona( 6498): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6498): v2
I/libpersona( 6498): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  897): Killing 5242:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 6498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6498): TimaSignature is unavailable
,D/ActivityThread( 6498): Added TimaKeyStore provider
,D/ResourcesManager( 6498): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 6498): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/dex2oat ( 6510): ----------------------------------------------------
I/dex2oat ( 6510): <SS>: S T A R T I N G . . .
I/dex2oat ( 6510): <SS>: going to process manifest...
I/        ( 6510): SS_ART_lib [I]: Processing Manifest...
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/        ( 6510): SS_ART_lib [I]: XML is parsed (58 > 55)
I/        ( 6510): SS_ART_lib [I]: XML is parsed (58 > 55)
,I/dex2oat ( 6510): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Zygote  ( 6528): MountEmulatedStorage()
,E/Zygote  ( 6528): v2
I/libpersona( 6528): KNOX_SDCARD checking this for 10086
I/libpersona( 6528): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.chaton for broadcast com.sec.chaton/.plugin.PlugInMonitor: pid=6528 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6528): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  897): failed to open /acct/uid_10045/pid_5242/cgroup.procs: No such file or directory
,I/art     (  312): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 12.754ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.981ms
,D/TimaKeyStoreProvider( 6528): TimaSignature is unavailable
,D/ActivityThread( 6528): Added TimaKeyStore provider
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.670ms
,D/ResourcesManager( 6528): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 6528): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1553): UpdateCorporaTask done [took 360 ms] updated apps [took 360 ms] 
,D/PushModule( 6528): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 6528): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 6528): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 6528): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 6528): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  897): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,I/GAV2    ( 6206): Thread[GAThread,5,main]: No campaign data found.
,D/ChatON  ( 6528): [1][a] ChatONV isn't installed.
D/ChatON  ( 6528): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/Zygote  ( 6552): MountEmulatedStorage()
I/libpersona( 6552): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6552): v2
I/libpersona( 6552): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5105:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/SELinux ( 6552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6552): TimaSignature is unavailable
,D/ActivityThread( 6552): Added TimaKeyStore provider
,D/ResourcesManager( 6552): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10078/pid_5105/cgroup.procs: No such file or directory
,I/dex2oat ( 6510): <SS>: going to form and sign ss id...
I/dex2oat ( 6510): dex2oat took 406.165ms (threads: 4)
,I/PackageManager(  897): do mInstaller.dexopt : 0
D/PackageManager(  897): Time to dexopt: 0.501 seconds
,W/System.err(  897): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err(  897): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  897): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err(  897): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5071)
W/System.err(  897): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:17035)
W/System.err(  897): 	at com.android.server.pm.PackageManagerService.access$5100(PackageManagerService.java:313)
W/System.err(  897): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:17020)
W/System.err(  897): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err(  897): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err(  897): 	... 5 more
,I/HarmonyEASService(  897): Updating for all 1
,D/PackageManager(  897): New package installed
,D/ShortcutReceiver( 6552):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  897): doPostInstall for uid{10200}
,D/PackageManager(  897): token 1 to BM for possible restore
,V/BackupManagerService(  897): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService(  897): Finishing install immediately
D/PackageManager(  897): BM finishing package install for 1
,E/Zygote  ( 6568): MountEmulatedStorage()
,E/Zygote  ( 6568): v2
I/libpersona( 6568): KNOX_SDCARD checking this for 10135
I/libpersona( 6568): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6568 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5751:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/PackageManager(  897): [MSG] MCS_UNBIND
,I/SELinux ( 6568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6568): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PackageManager(  897): [MSG] POST_INSTALL: observer{156013877}
D/PackageManager(  897):           Handling post-install for 1
,I/ActivityManager(  897): Killing 5767:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,W/Settings(  897): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,W/libprocessgroup(  897): failed to open /acct/uid_10025/pid_5751/cgroup.procs: No such file or directory
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/TimaKeyStoreProvider( 6568): TimaSignature is unavailable
,D/ActivityThread( 6568): Added TimaKeyStore provider
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  897): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1821): mOCRHelper is null
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager( 1492): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10067/pid_5767/cgroup.procs: No such file or directory
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 6568): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,V/BitmapFactory( 1492): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/icon.png
,W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,W/ResourcesManager( 6568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/EnterpriseDeviceManagerService(  897): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  897): Admin package name: com.google.android.gms
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     (  897): Explicit concurrent mark sweep GC freed 29893(2MB) AllocSpace objects, 9(144KB) LOS objects, 23% free, 50MB/66MB, paused 2.266ms total 269.138ms
,D/PackageManager(  897): result of install: 1{156013877}
,I/PackageManager(  897): Observer no longer exists.
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManagerService(  897): PackageReceiver onReceive()
D/RCPManagerService(  897): App Installed with packageNAme = com.test.thalitest
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/RCPManagerService(  897):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService(  897):  PackageReceiver onReceive() bundle null
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/KnoxMUMContainerPolicy(  897): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService(  897): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService(  897): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
,V/EnterpriseBillingPolicy(  897): uID is 10200
V/EnterpriseBillingPolicy(  897): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/PersonaPolicyManagerService(  897): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,D/KnoxMUMContainerPolicy(  897): packageInstalledForExternalStorage com.test.thalitest
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,V/AlarmManager(  897): waitForAlarm result :4
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/Zygote  ( 6597): MountEmulatedStorage()
E/Zygote  ( 6597): v2
I/libpersona( 6597): KNOX_SDCARD checking this for 10030
I/libpersona( 6597): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6597 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/CrashAnrDetector(  897): onPackageAdded : com.test.thalitest
I/SELinux ( 6597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6597): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/CheckinService( 2365): Done disabling old GoogleServicesFramework version
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,D/TimaKeyStoreProvider( 6597): TimaSignature is unavailable
,D/BatteryService(  897): level:100, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
D/ActivityThread( 6597): Added TimaKeyStore provider
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/ResourcesManager( 6597): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/GLSActivity( 1674): [ac] getting account id
,I/GLSUser ( 1674): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/Finsky  ( 6597): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6597): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6638): MountEmulatedStorage()
E/Zygote  ( 6638): v2
I/libpersona( 6638): KNOX_SDCARD checking this for 10012
I/libpersona( 6638): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6638 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6638): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6597): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6597): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6638): TimaSignature is unavailable
,D/ActivityThread( 6638): Added TimaKeyStore provider
,D/ResourcesManager( 6638): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6638): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6638): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6638): VM with version 2.1.0 has multidex support
I/MultiDex( 6638): install
I/MultiDex( 6638): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6597): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6597): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6597): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 6638): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SMD     (  286): DCD ON
,D/Finsky  ( 6597): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 2365): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/PeopleContactsSync( 2365): CP2 sync disabled
,I/ActivityManager(  897): Killing 5464:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): bgCount ##41
,D/ResourcesManager( 4582): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/UpdateIcingCorporaServi( 1553): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FileShare-Server( 6482): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,W/ActivityThread( 6638): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6638): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@aea6307: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6638): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  897): failed to open /acct/uid_10071/pid_5464/cgroup.procs: No such file or directory
,D/ShortcutReceiver( 6552):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/PackageBroadcastService( 2365): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  897): Killing 4654:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6679): MountEmulatedStorage()
E/Zygote  ( 6679): v2
I/libpersona( 6679): KNOX_SDCARD checking this for 1000
I/libpersona( 6679): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6679 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PackageBroadcastService( 2365): Null package name or gms related package.  Ignoreing.
,W/libprocessgroup(  897): failed to open /acct/uid_10091/pid_4654/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6679): TimaSignature is unavailable
,D/ActivityThread( 6679): Added TimaKeyStore provider
,D/ResourcesManager( 6679): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/Icing   ( 2365): updateResources: need to parse f{com.google.android.gms}
,I/DIAGMON_AGENT( 6679): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 6679): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/ResourcesManager( 6638): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager( 1553): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/UpdateIcingCorporaServi( 1553): UpdateCorporaTask done [took 280 ms] updated apps [took 280 ms] 
,I/ActivityManager(  897): Killing 5784:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,D/ResourcesManager( 6638): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/Finsky  ( 6597): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/libprocessgroup(  897): failed to open /acct/uid_10104/pid_5784/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6679): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6679): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6679): [com.diagmondm.XDMBroadcastReceiver(34/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager(  897): Killing 5587:com.samsung.android.securitylogagent/1000 (adj 15): bgCount ##41
,I/DBG_DM  ( 3795): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,V/TaskCloserActivity( 5892): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/CalendarAlarmManager( 4908): sys current time:1455009582675
,D/CalendarAlarmManager( 4908): reminder amount:0
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5587/cgroup.procs: No such file or directory
,D/WearableService( 4822): callingUid 10012, callindPid: 4822
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/MusicLeanback( 5343): Conditions not met for autocaching.
I/MusicLeanback( 5343): Stop autocaching.
,E/Zygote  ( 6703): MountEmulatedStorage()
E/Zygote  ( 6703): v2
I/libpersona( 6703): KNOX_SDCARD checking this for 1000
I/libpersona( 6703): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6703 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 5343): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 5343): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5343): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 5343): Using the GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6703): TimaSignature is unavailable
,D/ActivityThread( 6703): Added TimaKeyStore provider
,D/ResourcesManager( 6703): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,I/ActivityManager(  897): Waited long enough for: ServiceRecord{2ed6e35b u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/WearableClient( 5343): WearableClientImpl.onPostInitHandler: done
,E/MTPRx   ( 6703): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/WearableClient( 5343): WearableClientImpl.onPostInitHandler: done
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/WearableClient( 5343): WearableClientImpl.onPostInitHandler: done
,D/SecContentProvider2(  897): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,V/MTPRx   ( 6703): sealedState: false
V/MTPRx   ( 6703): sealedUsbMassStorageState: false
E/MTPRx   ( 6703): check value of boot_completed is1
E/MTPRx   ( 6703): check booting is completed_sys.boot_completed
,D/WearableClient( 5343): WearableClientImpl.onPostInitHandler: done
,E/MTPRx   ( 6703): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 6703): Status for mount/Unmount :removed
E/MTPRx   ( 6703): SDcard is not available
,W/MTPRx   ( 6703): value of connected istrue
W/MTPRx   ( 6703): value of configured istrue
W/MTPRx   ( 6703): value of mtpEnabled istrue
W/MTPRx   ( 6703): value of ptpEnabled isfalse
,E/MTPRx   ( 6703): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 6703): mFirstTime: false
,E/GmsUtils( 5343): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5343): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread( 5343): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@27ce7853 that was originally bound here
E/ActivityThread( 5343): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@27ce7853 that was originally bound here
E/ActivityThread( 5343): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 5343): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 5343): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 5343): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 5343): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5343): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 5343): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5343): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5343): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5343): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 5343): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 5343): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 5343): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 5343): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 5343): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 5343): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 5343): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 5343): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 5343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5343): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5343): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 5343): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5343): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5343): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5343): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/        ( 6703): MTP: reading debug level property
,E/MTPRx   ( 6703):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 6703): Getting CryptionKey from JAVA
E/MTPRx   ( 6703): currentUserId is 0
,E/MTPRx   ( 6703): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 6703): usbMode is 0210
,E/MTPRx   ( 6703): is_Privatemode is NOT 1
,D/SettingsProvider(  897): name = mtp_usb_conditions_met
,D/SecContentProvider(  897): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 6703): sending MTP_ICON_ENABLED to stack
,D/SettingsProvider(  897): name = mtp_running_status
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SettingsProvider(  897): name = mtp_usb_conditions_met
,E/MTPRx   ( 6703): else part ... so first time!!!
,E/MTPPlaObsrvr( 6703): inside setContext()
E/MTPPlaObsrvr( 6703):  inside createplafiles
,E/MTPPlaObsrvr( 6703): playlist count is0
E/MTPPlaObsrvr( 6703):  inside try branch createplafiles
,E/MTPPlaObsrvr( 6703):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 6703): Inside registerContentObserver
,E/MtpAdbObserver( 6703): inside setContext()
E/MtpAdbObserver( 6703): Inside registerContentObserver
W/Settings( 6703): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/SettingsProvider(  897): name = mtp_running_status
,D/SettingsProvider(  897): name = mtp_usb_conditions_met
,E/MtpService( 6703): onCreate.
,E/MtpService( 6703): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 6703): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 6703): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 6703): onStartCommand.
,W/MTPRx   ( 6703): calling native method
E/MTPJNIInterface( 6703): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 6703): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/MtpService( 1221): updating state; isCurrentUser=true, mMtpLocked=false
,E/MTPJNIInterface( 6703): < MTP > Registering BroadCast receiver :::::::
,D/TMNetworkReceiver( 5875): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = true, mIsFileUpdated= false
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() mThread.interrupt()
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() USB CONNECTED
,D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() Exit 
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() interrupted while sleeping 
D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() UsbCheck Thread Exit
,D/TMNetworkReceiver( 5875): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
,E/MTPJNIInterface( 6703): noti = 10
,D/TMSLogRemovalReceiver( 5875): TMLogRemovalReceiver.onReceive() Enter isCalled =true
D/TMSLogRemovalReceiver( 5875): TMLogRemovalReceiver.onReceive() Exit
,E/MtpService( 6703): onStartCommand.
,E/MtpService( 6703): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 6703): calling native method
E/MTPRx   ( 6703): Checking the driver time out
,E/MTPJNIInterface( 6703): noti = 2
D/        ( 6703): deleting sockets before message queue initialization
,D/        ( 6703): event handler thread is created, so set the flag
,D/MediaScannerReceiver( 1221): action: android.intent.action.MTP_FILE_SCAN
,E/MTPRx   ( 6703): called native method
E/MTPJNIInterface( 6703): setting Media scanner status0
E/MTPJNIInterface( 6703): After setting Media scanner status0
W/MTPRx   ( 6703): notification from stack 1
E/        ( 6703): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 6703): Getting media scanner status0
,E/MTPJNIInterface( 6703): DeviceName is Thali Test (Galaxy S5)
,I/SettingSearch/SearchIntentReceiver( 1302): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1302): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1302): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1302): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,D/BluetoothManager( 4700): getConnectedDevices
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor5:85000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor5:85000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 1
,I/SettingSearch/SettingsSearchManager( 1302): Infomation -> numtitleinfo : 0 numSearchinfo : 334
,D/MediaScannerService( 1221): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/Avrcp   ( 3221): Received the onChange database event
I/Avrcp   ( 3221): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 3221): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,V/AlarmManager(  897): waitForAlarm result :4
,D/Finsky  ( 6597): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/HomeSyncInstallReceiver( 1468): This pkg do not need BT addr. Do nothing
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter finished
,E/Zygote  ( 6746): MountEmulatedStorage()
,E/Zygote  ( 6746): v2
I/libpersona( 6746): KNOX_SDCARD checking this for 10015
I/libpersona( 6746): KNOX_SDCARD not a persona
,D/MediaScanner( 1221): Prescan. DB items number : 21 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/ActivityManager(  897): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6746 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/SSRM:m  (  897): SIOP:: AP = 490, PST = 445, CUR = 300
,I/SELinux ( 6746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6746): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6746): TimaSignature is unavailable
,D/ActivityThread( 6746): Added TimaKeyStore provider
I/art     (  897): Explicit concurrent mark sweep GC freed 193959(12MB) AllocSpace objects, 4(3MB) LOS objects, 30% free, 36MB/52MB, paused 3.385ms total 125.442ms
,D/ResourcesManager( 6746): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SettingSearch/SettingsSearchManager( 1302):  Infomation -> getItem size : 334
,W/Finsky  ( 6597): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/iu.UploadsManager( 2365): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,V/MediaScanner( 1221): processDirectory :  /storage/emulated/0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/MediaScanner( 1221): Skipping:
,D/MediaScanner( 1221): 7klwibgf7fvntblfd7(75ebcf7
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:86000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:86000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 86.0 degC
,E/Zygote  ( 6767): MountEmulatedStorage()
I/libpersona( 6767): KNOX_SDCARD checking this for 10016
E/Zygote  ( 6767): v2
I/libpersona( 6767): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=6767 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MediaScanner( 1221): Skipping:
D/MediaScanner( 1221): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1221): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1221): Error opening directory, reason : Permission denied.
W/MediaScanner( 1221): 7klwibgf7fxlKdCbid7
,I/SELinux ( 6767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6767): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
E/File    ( 1221): fail readDirectory() errno=2
,V/MediaScanner( 1221): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4ac61be
,V/MediaScanner( 1221): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4ac61be
,V/MediaScanner( 1221):  prescan time: 158ms (DB items: 21)
,V/MediaScanner( 1221):     scan time: 53ms (Caching mode: true), (makeEntry time: 20ms ~37%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1221): postscan time: 19ms (bulkDeleter : 0), (delete DeadThumbnail time : 7ms)
V/MediaScanner( 1221):    total time: 230ms
V/MediaScanner( 1221): checked files: 4  directories : 17  (I: 0, U: 0)
,D/ResourcesManager( 1302): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/MTPJNIInterface( 6703): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/MediaScannerService( 1221): !@done scanning volume external
,D/TimaKeyStoreProvider( 6767): TimaSignature is unavailable
,D/ActivityThread( 6767): Added TimaKeyStore provider
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1302): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,D/ResourcesManager( 6767): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/iu.UploadsManager( 2365): End new media; added: 0, uploading: 0, time: 137 ms
W/ResourcesManager( 6767): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6767): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1302): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 1302): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/MTPJNIInterface( 6703): Status for mount/Unmount :removed
E/MTPJNIInterface( 6703): SDcard is not available
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1302): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,W/Finsky  ( 6597): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/        ( 6703): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 6703): Status for mount/Unmount :removed
,E/MTPJNIInterface( 6703): SDcard is not available
E/SQLiteLog( 6703): (21) API call with NULL database connection pointer
D/GroupCast_FileTools( 6767): [getDirectoryForImageResized : 295] cleaning!!
E/SQLiteLog( 6703): (21) misuse at line 105654 of [9491ba7d73]
,E/SQLiteLog( 6703): (21) API call with NULL database connection pointer
E/SQLiteLog( 6703): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6703): (21) API call with NULL database connection pointer
E/SQLiteLog( 6703): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6703): (21) API call with NULL database connection pointer
,E/SQLiteLog( 6703): (21) misuse at line 105654 of [9491ba7d73]
,W/MTPRx   ( 6703): notification from stack 2
,D/        ( 6703): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 6703): [mtp_init_device 692]  After open the MTP fd = 32 and line = 692...
D/        ( 6703): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 6703):  [sua_support_present:1275] returning false 
D/        ( 6703): *****Starting mtp_io()
,W/MTPRx   ( 6703): notification from stack 3
D/        ( 6703): [mtp_start_io] source_thread Creation 
D/        ( 6703): [mtp_start_io] sink_thread Creation 
D/        ( 6703): [mtp_start_io:368] sink thread created so set th_sink
,W/System.err( 6767): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,W/System.err( 6767): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 6767): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 6767): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 6767): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6767): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 6767): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6767): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6767): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6767): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6767): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6767): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6788): MountEmulatedStorage()
E/Zygote  ( 6788): v2
I/libpersona( 6788): KNOX_SDCARD checking this for 1000
I/libpersona( 6788): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6788 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6788): TimaSignature is unavailable
,D/ActivityThread( 6788): Added TimaKeyStore provider
,V/Avrcp   ( 3221): handleMessage, msg=207
D/BluetoothMediaBrowser( 3221):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/ResourcesManager( 6788): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/BluetoothMediaBrowser( 3221): no now playing list
D/BluetoothMediaBrowser( 3221):  getNowPlayingId now playing id : -1
D/Avrcp   ( 3221):  checkNowPlayingList start
,I/PCWCLIENTTRACE_LOG( 6788): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 6788): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6788): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6788): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6788): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6788): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6788): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6803): MountEmulatedStorage()
E/Zygote  ( 6803): v2
I/libpersona( 6803): KNOX_SDCARD checking this for 1000
I/libpersona( 6803): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=6803 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5820:com.sec.android.app.taskmanager/u0a176 (adj 15): bgCount ##41
,I/SELinux ( 6803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6803): TimaSignature is unavailable
,D/ActivityThread( 6803): Added TimaKeyStore provider
,D/ResourcesManager( 6803): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10176/pid_5820/cgroup.procs: No such file or directory
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6823): MountEmulatedStorage()
,E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD checking this for 10045
I/libpersona( 6823): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6823 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5835:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,I/art     (  312): Explicit concurrent mark sweep GC freed 8784(373KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 10.842ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 8.160ms
,I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 261us total 8.349ms
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/ActivityManager(  897): Killing 5908:com.sec.factory/1000 (adj 15): bgCount ##41
,I/SettingSearch/SearchIntentReceiver( 1302): LOCALE_CHANGED call search setting db finish!!
,D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
,D/ActivityThread( 6823): Added TimaKeyStore provider
,D/ResourcesManager( 6823): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5835/cgroup.procs: No such file or directory
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5908/cgroup.procs: No such file or directory
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6823): [SSP] onCreated
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SA      ( 6823): [TPM] There is no property file
,I/SA      ( 6823): [SCU] isHaveSA() - false
,I/SA      ( 6823): [TPM] getModelProperty : null
I/SA      ( 6823): [TPM] getCSCProperty : null
,I/SA      ( 6823): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SettingSearch/SearchIntentReceiver( 1302): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1302): LOCALE_CHANGED call search setting db finish!!
,I/SA      ( 6823): [DM] init START
,I/SA      ( 6823): [DM] This device is not a Vodafone
,W/ResourceType( 6823): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 6823): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6823): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 6823): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6823): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6823): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 6823): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 6823): [SCU] isHaveSA() - false
I/SA      ( 6823): support phone number id : false
,I/SA      ( 6823): [DM] init END
,I/SA      ( 6823): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6823): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10200 extra.user_handle.:0 ]
,I/ActivityManager(  897): Killing 5931:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,D/Mms/FreeMessageReceiver( 5722): onReceive, action : android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5931/cgroup.procs: No such file or directory
,D/Mms/FreeMessageReceiverService( 5722): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5722): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 6844): MountEmulatedStorage()
I/libpersona( 6844): KNOX_SDCARD checking this for 10051
E/Zygote  ( 6844): v2
I/libpersona( 6844): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6844 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 6844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6844): TimaSignature is unavailable
,D/ActivityThread( 6844): Added TimaKeyStore provider
,W/Finsky  ( 6597): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6597): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ResourcesManager( 6844): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 6844): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6844): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/Finsky  ( 6597): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6597): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,I/ActivityManager(  897): Killing 5956:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/ActivityManager(  897): Killing 6032:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##42
,I/art     ( 2069): Explicit concurrent mark sweep GC freed 25733(1497KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 18MB/30MB, paused 470us total 33.730ms
,D/DeviceConnectionService( 2069): client connected with version: 7571000
,I/ActivityManager(  897): Waited long enough for: ServiceRecord{39c1ee34 u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
,D/MyFiles ( 6844): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,E/installd(  294): system dir 0 : /system/app/
E/installd(  294): system dir 1 : /system/priv-app/
E/installd(  294): system dir 2 : /vendor/app/
E/installd(  294): system dir 3 : /oem/app/
,I/TactileAssist(  897): enable value -1
,I/TactileAssist(  897): internal enable value -1
I/TactileAssist(  897): intensity value -1
I/TactileAssist(  897): saveAppList value true
W/libprocessgroup(  897): failed to open /acct/uid_10002/pid_6032/cgroup.procs: No such file or directory
,W/libprocessgroup(  897): failed to open /acct/uid_10004/pid_5956/cgroup.procs: No such file or directory
,I/TactileAssist(  897): List of disabled apps :
,I/TactileAssist(  897): de.zalando.mobile
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  897): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/Zygote  ( 6862): MountEmulatedStorage()
I/libpersona( 6862): KNOX_SDCARD checking this for 10058
E/Zygote  ( 6862): v2
I/libpersona( 6862): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6862 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6862): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6862): TimaSignature is unavailable
,D/ActivityThread( 6862): Added TimaKeyStore provider
,D/ResourcesManager( 6862): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 6862): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 6862): onReceive() it will make start service
,D/Compatibility( 6862): onHandleIntent()
,D/Compatibility( 6862): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10200, android.intent.extra.user_handle=0}]
,D/Compatibility( 6862): found: 2
,D/Compatibility( 6862): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6862): skipping ResolveInfo{e083ac8 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6862): considering ResolveInfo{3a1a2761 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6862): default: com.sec.android.app.soundalive.SAControlPanelActivity
,I/UpdateIcingCorporaServi( 1553): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 6862): enabling receiver ResolveInfo{b288286 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 6862): enabling receiver ResolveInfo{11a89747 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 6281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,D/Compatibility( 6862): enabling receiver ResolveInfo{2aca3b74 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 6862): enabling receiver ResolveInfo{5f0d89d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 6862): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6882): MountEmulatedStorage()
,E/Zygote  ( 6882): v2
I/libpersona( 6882): KNOX_SDCARD checking this for 10098
I/libpersona( 6882): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6882 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 1553): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/UpdateIcingCorporaServi( 1553): UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,I/SELinux ( 6882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  897): Killing 5996:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,E/SELinux ( 6882): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6882): TimaSignature is unavailable
,D/ActivityThread( 6882): Added TimaKeyStore provider
,D/ResourcesManager( 6882): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10044/pid_5996/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): Sensor:tsens_tz_sensor5:75000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor5:75000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm cleared 1 at 75.0 degC
I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 74.0 degC
,I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 0
,D/DocsApplication( 6882): Installing DEX configuration.
,D/DexInstaller( 6882): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 6882): Provided clientMode=RELEASE, packageInfo=PackageInfo{3e346f6b com.google.android.apps.docs}
,D/TAG     ( 6882): onCreate()
,D/CrossAppStateProvider( 6882): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6909): MountEmulatedStorage()
,E/Zygote  ( 6909): v2
I/libpersona( 6909): KNOX_SDCARD checking this for 10099
I/libpersona( 6909): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=6909 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6111:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,I/SELinux ( 6909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/GAV2    ( 6882): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/SELinux ( 6909): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6909): TimaSignature is unavailable
,D/ActivityThread( 6909): Added TimaKeyStore provider
,W/libprocessgroup(  897): failed to open /acct/uid_10172/pid_6111/cgroup.procs: No such file or directory
,D/ResourcesManager( 6909): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 6909): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 6909): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 6909): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 6909): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6942): MountEmulatedStorage()
E/Zygote  ( 6942): v2
I/libpersona( 6942): KNOX_SDCARD checking this for 10033
I/libpersona( 6942): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=6942 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 6942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6942): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6942): TimaSignature is unavailable
,D/ActivityThread( 6942): Added TimaKeyStore provider
,D/ResourcesManager( 6942): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6942): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 6942): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 6942): Inside WakeupProvider
,W/GAV2    ( 6882): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/DatabaseUtils( 6942): Writing exception to parcel
E/DatabaseUtils( 6942): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 6942): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 6942): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 6942): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 6942): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 6942): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 6942): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 6942): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 6942): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6942): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6942): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 6909): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 6909): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 6909): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 6909): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 6909): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 6909): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 6909): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 6909): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 6909): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 6909): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 6909): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 6909): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 6909): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 6909): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 6909): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 6909): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 6909): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6909): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 6909): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6909): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6909): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6909): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 6942): Writing exception to parcel
E/DatabaseUtils( 6942): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 6942): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 6942): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 6942): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 6942): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 6942): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 6942): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 6942): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 6942): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6942): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6942): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 6909): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 6909): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 6909): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 6909): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 6909): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 6909): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 6909): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 6909): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 6909): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 6909): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 6909): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 6909): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 6909): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 6909): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 6909): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6909): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 6909): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6909): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6909): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6909): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 6909): [DLApplication]-Init Called!:false
E/[CarMode]( 6909): [DLApplication]-Init Started!:true
I/[CarModeFW]( 6909): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 6909): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 6909): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 6909): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 6909): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 6909): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 6909): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 6909): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 6909): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 6909): ### android.os.Looper::loop(145)
I/[CarModeFW]( 6909): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 6909): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 6909): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 6909): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication( 6942): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
I/VlingoAndroidCore( 6942): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
I/MessageDataHandler( 6909): initialize
,D/[CarModeFW]( 6909): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 6909): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 6909): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 6909): CDH-ContactDataHandler initiazlieCaches time : 23
D/[CarModeFW]( 6909): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 6909): DrivingManager-initialize...
I/SensorService(  897): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  897): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  897): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 6942): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 6942): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 6909): Need to enable context aware info
V/MediaPlayer-JNI( 6909): native_setup
V/MediaPlayer( 6909): constructor
,V/MediaPlayer( 6909): setListener
E/MediaPlayer-JNI( 6909): QCMediaPlayer mediaplayer NOT present
,I/art     (  897): Explicit concurrent mark sweep GC freed 23742(1408KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 1.278ms total 81.319ms
,D/[CarModeFW]( 6909): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 6909): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 6909): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1455009585867
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1455009585867
D/[CarMode]( 6909): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1455009585867
,D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1455009585868
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1455009585868
,D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1455009585869
,D/TP/SmsProvider( 1477): query,matched:2, calling pid = 6909
D/TP/SmsProvider( 1477): query,matched:2, calling pid = 6909
,D/TP/SmsProvider( 1477): match 2:Elapsed time : 1.631 ms
,D/TP/SmsProvider( 1477): match 2:Elapsed time : 1.578 ms
,D/MessageDataHandler( 6909):  getInboxList smsCursor : 12
,I/[CarMode]( 6909): [LogNotNull]-Package name is: com.google.android.apps.maps
D/[CarModeFW]( 6909): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsProvider( 1477): Query uri=content://mms/inbox, match=2, calling pid = 6909
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6980): MountEmulatedStorage()
I/libpersona( 6980): KNOX_SDCARD checking this for 10003
E/Zygote  ( 6980): v2
I/libpersona( 6980): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=6980 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/[CarMode]( 6909): [DLApplication]-Init End!:true
,D/[CarModeFW]( 6909): RecommendHandler-selection = type = '3'
,I/SELinux ( 6980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 6909):  getInboxList mmsCursor : 39
I/SELinux ( 6980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler( 6909):  getInboxList mms,sms cursor join : 5
,D/TP/MmsProvider( 1477): Query uri=content://mms, match=0, calling pid = 6909
,D/TP/MmsSmsProvider( 1477): query,matched:0, calling pid = 6909
V/TP/MmsSmsProvider( 1477): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1477): match 0:Elapsed time : 1.207 ms
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/Zygote  ( 6995): MountEmulatedStorage()
,E/Zygote  ( 6995): v2
I/libpersona( 6995): KNOX_SDCARD checking this for 10020
I/libpersona( 6995): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=6995 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/[CarModeFW]( 6909): CDH-buildContactCacheWireFrame : cur len =0
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/SELinux ( 6995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6995): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6980): TimaSignature is unavailable
,D/ActivityThread( 6980): Added TimaKeyStore provider
,D/[CarMode]( 6909): [DLApplication]-GooglePlayServices SUCCESS.
,I/MessageDataHandler( 6909): getUnreadMessageCount :0
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 125
,E/[CarMode]( 6909): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/TP/MmsSmsProvider( 1477): query,matched:13, calling pid = 6909
,D/TP/MmsSmsProvider( 1477): match 13:Elapsed time : 1.467 ms
,D/[CarModeFW]( 6909): CDH-buildContactCacheWireFrame : cur len =0
,I/UpdateManagerReceiver( 6909): Intent : android.intent.action.PACKAGE_ADDEDTue Feb 09 10:19:46 GMT+01:00 2016
,D/MessageDataHandler( 6909):  getInboxList address cursor : 11
,D/ResourcesManager( 6980): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/TP/MmsSmsProvider( 1477): query,matched:0, calling pid = 6909
V/TP/MmsSmsProvider( 1477): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1477): match 0:Elapsed time : 0.913 ms
,D/TimaKeyStoreProvider( 6995): TimaSignature is unavailable
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 6995): Added TimaKeyStore provider
,E/Zygote  ( 7015): MountEmulatedStorage()
E/Zygote  ( 7015): v2
,I/libpersona( 7015): KNOX_SDCARD checking this for 1000
I/libpersona( 7015): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 6909): RecommendHandler-selection = type = '3'
,D/UserAnalysis.PlaceProvider( 6980): PlaceProvider onCreate()
,D/MessageDataHandler( 6909):  getInboxList thread cursor : 62
,I/ActivityManager(  897): Killing 6137:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/MessageDataHandler( 6909):  thread, addr result: 6
,D/[CarModeFW]( 6909): PushMessageService-onCreate
,I/[CarModeFW]( 6909): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 207
I/[CarModeFW]( 6909): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 207
,I/ActivityManager(  897): Killing 6172:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,I/ActivityManager(  897): Killing 5801:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##42
,I/ActivityManager(  897): Killing 6156:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##43
,D/TimaKeyStoreProvider( 7015): TimaSignature is unavailable
,D/ActivityThread( 7015): Added TimaKeyStore provider
,D/ResourcesManager( 6995): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/[CarModeFW]( 6909): PushMessageManager-onServiceConnected
,D/[CarModeFW]( 6909): PushMessageService-registerPushMessageServiceListener
,D/ResourcesManager( 7015): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,W/ContextImpl( 7015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7015): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7031): MountEmulatedStorage()
I/libpersona( 7031): KNOX_SDCARD checking this for 10112
E/Zygote  ( 7031): v2
I/libpersona( 7031): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7031 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 6980): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6980): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 6980): Create SecureDbHelper
,I/SELinux ( 7031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/FilterInstaller( 7015): There is no requred permission
,E/SELinux ( 7031): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  897): Killing 6191:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,D/IntelligenceServiceApplication( 6980): onCreate()
,D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 315
,D/TimaKeyStoreProvider( 7031): TimaSignature is unavailable
,D/ActivityThread( 7031): Added TimaKeyStore provider
,I/SQLiteSecureOpenHelper( 6980): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 6980): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 6980): Open Place.db in secure mode
,I/[CarModeFW]( 6909): -[snowdeer] Rec : Missed Call : 303
,D/ResourcesManager( 7031): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/[CarModeFW]( 6909): -[snowdeer] Rec : Favorite : 8
,I/[CarModeFW]( 6909): -[snowdeer] Rec : CallLog : 9
,D/PackageIntentReceiver( 7031): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7031): Not GearManger package! 
,I/SQLiteSecureOpenHelper( 6980): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 6980): ...getDatabaseLocked(b,b,pwd)
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7050): MountEmulatedStorage()
,E/Zygote  ( 7050): v2
I/libpersona( 7050): KNOX_SDCARD checking this for 10118
I/libpersona( 7050): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7050 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6368:com.sec.android.app.sns3/u0a36 (adj 15): bgCount ##41
,I/SELinux ( 7050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7050): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 395
,W/libprocessgroup(  897): failed to open /acct/uid_10094/pid_6137/cgroup.procs: No such file or directory
,W/libprocessgroup(  897): failed to open /acct/uid_10103/pid_6156/cgroup.procs: No such file or directory
D/[CarModeFW]( 6909): MyPlaceProvider-+++Begin print all data in content provider+++
W/libprocessgroup(  897): failed to open /acct/uid_10113/pid_5801/cgroup.procs: No such file or directory
D/[CarModeFW]( 6909): MyPlaceProvider-=============
W/libprocessgroup(  897): failed to open /acct/uid_10154/pid_6172/cgroup.procs: No such file or directory
,D/[CarModeFW]( 6909): MyPlaceProvider-=============
D/[CarModeFW]( 6909): MyPlaceProvider-=============
I/[CarModeFW]( 6909): -[snowdeer] Rec : Schedule : 47
,I/[CarModeFW]( 6909): -[snowdeer] Rec : During DL app : 1
,D/[CarModeFW]( 6909): MyPlaceProvider-=============
D/[CarModeFW]( 6909): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 6909): MyPlaceProvider-==============
D/[CarModeFW]( 6909): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 6909): MyPlaceProvider-==============
D/[CarModeFW]( 6909): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 6909): MyPlaceProvider-==============
D/[CarModeFW]( 6909): MyPlaceProvider-latitude is not valid
I/[CarModeFW]( 6909): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 6909): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 6909): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 400
,D/[CarModeFW]( 6909): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 399
,D/[CarMode]( 6909): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@1a8685fd, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@585b66af] LOCATIONS
,D/TimaKeyStoreProvider( 7050): TimaSignature is unavailable
,D/ActivityThread( 7050): Added TimaKeyStore provider
,W/libprocessgroup(  897): failed to open /acct/uid_10054/pid_6191/cgroup.procs: No such file or directory
,D/ResourcesManager( 7050): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7050): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  897): failed to open /acct/uid_10036/pid_6368/cgroup.procs: No such file or directory
,D/MagazineService Version( 7050): Magazine-Administrator: 11
,D/MagazineService Version( 7050): Magazine-Provider: 14
,D/MagazineService Version( 7050): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7050): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7050): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7050): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7066): MountEmulatedStorage()
I/libpersona( 7066): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7066): v2
I/libpersona( 7066): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7050): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/art     (  312): Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 11.262ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.473ms
,I/SELinux ( 7066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  897): Killing 5316:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,E/SELinux ( 7066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 516us total 9.685ms
,D/TimaKeyStoreProvider( 7066): TimaSignature is unavailable
,D/ActivityThread( 7066): Added TimaKeyStore provider
,D/ResourcesManager( 7066): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7081): MountEmulatedStorage()
I/libpersona( 7081): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7081): v2
I/libpersona( 7081): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 4848:com.android.calendar/u0a150 (adj 15): bgCount ##41
,I/SELinux ( 7081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  897): failed to open /acct/uid_10149/pid_5316/cgroup.procs: No such file or directory
,E/SELinux ( 7081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7081): TimaSignature is unavailable
,D/ActivityThread( 7081): Added TimaKeyStore provider
,D/ResourcesManager( 7081): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10150/pid_4848/cgroup.procs: No such file or directory
,I/ActivityManager(  897): Killing 6399:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): bgCount ##41
,D/AcmsPackageEventListener( 7081): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7081): Enter Oncreate
D/AcmsServiceMonitor( 7081): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7081): creating AcmsCore
D/AcmsCore( 7081): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7081): AcmsCore
,D/AcmsCore( 7081): init
D/AcmsCore( 7081): Looper handler is not null
D/AcmsCore( 7081): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7081): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7081): Incrementing - Counter value: 1
D/AcmsCore( 7081): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7081): onStartCommand
,D/AcmsCertificateMngr( 7081): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7081): AcmsRevocationMngr
,D/AcmsService( 7081): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7081): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7081): Incrementing - Counter value: 2
D/AcmsService( 7081): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7081): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,I/System.out( 6942): INFO:Resource not found:/Common.properties Using default values
,D/AcmsService( 7081): Inside handle Intent
D/AcmsService( 7081): App added - package name: com.test.thalitest
D/AcmsCore( 7081): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7081): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7081): Incrementing - Counter value: 3
D/AcmsCore( 7081): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7081): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7081): Decrementing - Counter value: 2
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  897): failed to open /acct/uid_10038/pid_6399/cgroup.procs: No such file or directory
,E/Zygote  ( 7101): MountEmulatedStorage()
E/Zygote  ( 7101): v2
I/libpersona( 7101): KNOX_SDCARD checking this for 10166
I/libpersona( 7101): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7101 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 6568): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 7101): TimaSignature is unavailable
,D/ActivityThread( 7101): Added TimaKeyStore provider
,D/ResourcesManager( 7101): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7101): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7119): MountEmulatedStorage()
,E/Zygote  ( 7119): v2
I/libpersona( 7119): KNOX_SDCARD checking this for 10170
I/libpersona( 7119): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7119 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 7119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  897): Killing 6418:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7119): TimaSignature is unavailable
,D/ActivityThread( 7119): Added TimaKeyStore provider
,D/ResourcesManager( 7119): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7119): (284) automatic index on shooting_modes(title_id)
,W/libprocessgroup(  897): failed to open /acct/uid_10038/pid_6418/cgroup.procs: No such file or directory
,I/ActivityManager(  897): Killing 6303:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2365): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 2365): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 2365): Failed to find package metadata for com.test.thalitest
D/Vision  ( 2365): No vision deps
,I/ConfigFetchService( 2365): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/Zygote  ( 7136): MountEmulatedStorage()
I/libpersona( 7136): KNOX_SDCARD checking this for 10040
E/Zygote  ( 7136): v2
I/libpersona( 7136): KNOX_SDCARD not a persona
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
I/ConfigFetchService( 2365): launchTask
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ActivityManager(  897): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7136 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7136): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  897): failed to open /acct/uid_10117/pid_6303/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 2365): CP2 sync disabled
,D/ResourcesManager( 2365): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/TimaKeyStoreProvider( 7136): TimaSignature is unavailable
,D/ActivityThread( 7136): Added TimaKeyStore provider
,D/ResourcesManager( 7136): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,V/ConfigFetchTask( 2365): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XZgQtY01jesztXeoUQJfOvCIyniPPwZrqLd55JJ3QrMG828lEJgbk5d6XPKngmbB9mMtxNuW317vVqjPZdAfdGjhqsUIj-HptRl9wK-jBwrBVKUXZ3I3O1ap0QpB1uYVbw173knoy087uihcsknEdIicbU65xGaK0WfV3wfxTT2nAPCPd8CBOoxffsOJC6zz-j7yU1o-tWgth1c0PMe-RonfXV9eRBeL6SPuWqz1GtaqYaBL0
,I/GoogleURLConnFactory( 2365): Using platform SSLCertificateSocketFactory
,I/System.out( 2365): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2365): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2365): (HTTPLog)-Thread-315-91991684: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2365): Tagging socket 88 with tag 40b00000000{1035,0} uid -1, pid: 2365, getuid(): 10012
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  897): Killing 6482:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/GCM     ( 1674): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2365): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/qtaguid ( 2365): Tagging socket 95 with tag 40b00000000{1035,0} uid -1, pid: 2365, getuid(): 10012
,E/MDM     ( 2069): [228] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/libprocessgroup(  897): failed to open /acct/uid_10075/pid_6482/cgroup.procs: No such file or directory
,D/LocationInitializer( 2365): Restart initialization of location
,E/CscFactoryReceiver( 1477): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1477): Media DB Scanner finished.
D/CscFactoryReceiver( 1477): start service to Set Ringtone
,D/CscFactoryReceiver( 1477): start service to Set Notification
,D/CscFactoryReceiver( 1477): start service to Set Alarmtone
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1477): onStart
,E/CscUpdateService( 1477): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1477): only ringtone update
,D/CscUpdateService( 1477): onStart
,E/CscUpdateService( 1477): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1477): only notification update
,E/Zygote  ( 7160): MountEmulatedStorage()
I/libpersona( 7160): KNOX_SDCARD checking this for 10004
E/Zygote  ( 7160): v2
I/libpersona( 7160): KNOX_SDCARD not a persona
D/CscUpdateService( 1477): onStart
,E/CscUpdateService( 1477): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1477): only alarmtone update
,E/CscParser( 1477): update(): xml file exist
E/CscParser( 1477): update(): xml file exist
,I/ActivityManager(  897): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=7160 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/CscParser( 1477): update(): xml file exist
,W/CSCSettings( 1477): Setting Ringtones (type) : 2
,D/CscParser( 1477): MessageTone: null
W/CSCSettings( 1477): 1. Tag_Str: null
,W/CSCSettings( 1477): Setting Ringtones (type) : 4
,D/CscParser( 1477): AlarmTone: null
W/CSCSettings( 1477): 1. Tag_Str: null
,I/SELinux ( 7160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7160): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/CSCSettings( 1477): Setting Ringtones (type) : 1
,D/CscParser( 1477): RingTone: null
W/CSCSettings( 1477): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 7160): TimaSignature is unavailable
,D/ActivityThread( 7160): Added TimaKeyStore provider
,D/ResourcesManager( 7160): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,I/qtaguid ( 2365): Untagging socket 88
,I/ConfigFetchService( 2365): fetch service done; releasing wakelock
,I/ConfigFetchService( 2365): stopping self
,I/DCMProvider( 7160): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@3e346f6b Provider Ref Count:1
,I/DCMConfig( 7160): [#DCM#] initializeTransport.SystemBroadcastReceiver  5 ms
,I/StorageController( 7160): [#DCM#]  state through storage volume =  mounted
,I/StorageController( 7160): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 7160): [#DCM#]  state through storage volume =  unmounted
I/StorageController( 7160): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
,I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
I/StorageController( 7160): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
I/StorageController( 7160): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager( 7160): [#DCM#] setCriticalStateFromSystem screenOn =  true high siop = false camera running = false
,I/DCMPolicyManager( 7160): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig( 7160): [#DCM#] initializeTransport.DCMPolicyManager  27 ms
,I/DCMConfig( 7160): [#DCM#] initializeTransport.MediaManager  32 ms
,I/DCMConfig( 7160): [#DCM#] initializeTransport.DCMNRTManager  53 ms
,I/DCMConfig( 7160): [#DCM#] No of CPU Core 4
,I/DCMConfig( 7160): [#DCM#] initializeTransport took  54 ms
I/DCMProvider( 7160): [#DCM#] onCreate end 
,I/DCMNRTManager( 7160): [#DCM#] intialize 
,I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  11 microsec. 
,I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  13 microsec. 
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
,I/StorageController( 7160): [#DCM#]  state through storage volume =  mounted
,E/Zygote  ( 7179): MountEmulatedStorage()
I/libpersona( 7179): KNOX_SDCARD checking this for 10007
E/Zygote  ( 7179): v2
I/libpersona( 7179): KNOX_SDCARD not a persona
,I/StorageController( 7160): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/ActivityManager(  897): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=7179 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/WriterFactory( 7160): [#DCM#] verifyLuceneDB ++ 
,I/WriterFactory( 7160): [#DCM#] verifyLuceneDB OK breaking 
,I/WriterFactory( 7160): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory( 7160): [#DCM#] TAXO in mode CREATE_OR_APPEND
,I/SELinux ( 7179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/StorageController( 7160): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 7160): [#DCM#]  state through storage volume =  unmounted
I/StorageController( 7160): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/SELinux ( 7179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/StorageController( 7160): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
E/SELinux ( 7179): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/StorageController( 7160): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 7160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7160): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController( 7160): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController( 7160): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/DCMUtilities( 7160): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,D/TimaKeyStoreProvider( 7179): TimaSignature is unavailable
,D/ActivityThread( 7179): Added TimaKeyStore provider
,I/SystemUtils( 7160): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
,I/SystemUtils( 7160): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities( 7160): [#DCM#] OSUpgrade not required 
I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7160): [#DCM#] onReceive action = EVENT_SIOP
I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
I/SystemBroadcastReceiver( 7160): [#DCM#] No one is registered with Event Id EVENT_NETWORK_CHANGED
,D/ResourcesManager( 7179): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,I/WriterFactory( 7160): [#DCM#] Before facet 
,I/WriterFactory( 7160): [#DCM#] After facet=!null ? true
,I/DCMUtilities( 7160): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController( 7160): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
,I/DCMConfig( 7160): [#DCM#] setSuccessState =  true
,I/ThumbnailProvider( 7179): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 7179): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 7179): [START] processBroadcastIntent ...
,I/BroadcastProcessorService( 7179): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7198): MountEmulatedStorage()
E/Zygote  ( 7198): v2
I/libpersona( 7198): KNOX_SDCARD checking this for 10044
I/libpersona( 7198): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=7198 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/SELinux ( 7198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7198): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SystemInfo( 7179): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 7179): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 7179): [START] DocumentService startDocumentService
,I/DocumentService( 7179): DocumentService onCreate ... service
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
D/TimaKeyStoreProvider( 7198): TimaSignature is unavailable
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/ActivityThread( 7198): Added TimaKeyStore provider
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/ResourcesManager( 7198): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7198): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7198): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7198): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7198): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7198): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7198): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SystemInfo( 7179): [SIOP LEVEL] : 0
,I/DocumentServiceUtils( 7179):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
,E/SystemInfo( 7179): DocumentService [SIOP LEVEL] changed to 0
E/SystemInfo( 7179): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,I/DocumentService( 7179): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7179): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 7179): fail readDirectory() errno=13
E/File    ( 7179): fail readDirectory() errno=13
,I/SystemInfo( 7179): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 7179): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 7179): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :29
E/DocumentService( 7179): [THUMBNAIL] Total Time taken for each file :0
E/        ( 7179): [INDEX] Total time taken for each file :0
,I/DocumentService( 7179): DocumentService onDestroy start
,I/DocumentService( 7179): DocumentService onDestroy end
,I/ActivityManager(  897): Killing 6498:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/DocumentService( 7179): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 7179): InterruptedException: null
,I/SystemInfo( 7179): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 7179): DocumentService cleanupEverything end
,I/Process ( 7179): Sending signal. PID: 7179 SIG: 9
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/GalleryCacheReady( 6015): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/ActivityManager(  897): Process com.samsung.indexservice (pid 7179)(adj 9) has died(62,629)
,D/GalleryCacheReady( 6015): handleMeidaScanFinish()
,D/FaceInterface( 6015): requestFaceScan() is called.
,I/FaceInterface( 6015): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 6015): query fail: 
,W/LocalSuggestAlbumData( 6015): query fail: 
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6498/cgroup.procs: No such file or directory
,D/BootupListener( 1477): ACTION_DRIVELINK
D/SettingsProvider(  897): name = drivelink_navigation
D/SettingsProvider(  897): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  897): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  897): selectionArgs: false
D/SettingsProvider(  897): selectionArgs: 1001
D/SecContentProvider(  897): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  897): ret = -1
,D/BootupListener( 1477): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  897): name = internet_call_settings_visibility
D/SettingsProvider(  897): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  897): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  897): selectionArgs: false
D/SettingsProvider(  897): selectionArgs: 1001
,D/SecContentProvider(  897): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  897): ret = -1
,W/ProcessCpuTracker(  897): Skipping unknown process pid 7179
,I/MediaStoreImporter( 5343): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/GAV2    ( 6882): Thread[GAThread,5,main]: No campaign data found.
,D/AcmsKeyStoreHelper( 7081):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7081): Key Store exist
I/AcmsKeyStoreHelper( 7081): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 7081):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7081): getKeyStoreForApplication success 
D/AcmsCore( 7081): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7081): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7081): Decrementing - Counter value: 1
D/AcmsCore( 7081): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7081): This is NOT a valid MirrorLink app
D/AcmsCore( 7081): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7081): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7081): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7081): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7081): getSvcCounter - Counter value: 0
D/AcmsService( 7081): Enter onDestroy
I/AcmsService( 7081): cleanUp(): inside service clean up
D/AcmsCore( 7081): AcmsCore: inside DeInit
D/AcmsCore( 7081): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7081): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7081): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7081): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7081): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 7081): getSvcCounter - Counter value: 0
D/AcmsService( 7081): killing acms process
I/Process ( 7081): Sending signal. PID: 7081 SIG: 9
,I/ActivityManager(  897): Process ACMS.Process (pid 7081)(adj 0) has died(79,634)
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/SMD     (  286): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ActivityManager(  897): Killing 6552:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6552/cgroup.procs: No such file or directory
,I/ConfigService( 1674): onDestroy
,D/PowerManagerService(  897): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  897): lcd : 28 +
,D/lights  (  897): lcd : 28 -
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,D/lights  (  897): lcd : 15 +
,D/lights  (  897): lcd : 15 -
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,I/FaceInterface( 6015): startFaceScan() : going on
,D/FaceInterface( 6015): startFaceScan() is called.
,I/art     (  897): Explicit concurrent mark sweep GC freed 22747(1350KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.532ms total 124.668ms
,D/ContentApp( 1221): startScan() is called.
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1221): isNeedToRestore : start
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:2, health:2, present:true, voltage: 4348, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager(  897): waitForAlarm result :4
,D/SSRM:m  (  897): SIOP:: AP = 460, PST = 448, CUR = 300
,I/iu.UploadsManager( 2365): End new media; added: 0, uploading: 0, time: 69 ms
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/SMD     (  286): DCD ON
,D/PackageManager(  897): [MSG] MCS_UNBIND
,I/ActivityManager(  897): Killing 6679:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6679/cgroup.procs: No such file or directory
,I/ActivityManager(  897): Waited long enough for: ServiceRecord{3c196fbc u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  286): DCD ON
,I/ActivityManager(  897): Waited long enough for: ServiceRecord{12ccee00 u0 com.samsung.android.MtpApplication/.MtpService}
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/PowerManagerService(  897): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  897): Nap time (uid 1000)...
,I/PowerManagerService(  897): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  897): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  897): setDeviceInteractive: 0
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  897): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  897): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  897): handleSandman : startDream()
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  897): handleSandman : startDreaming, but isDreaming false
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,I/PowerManagerService(  897): Sleeping (uid 1000)...
,D/PowerManagerService(  897): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  897): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  897): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,D/SContextService(  897): 	.unregisterCallback : 1, client=
,D/SContextService(  897): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@16a366dd, Service = Auto Rotation, used = 1
,I/Adreno-EGL(  897): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  897): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  897): Build Date: 03/03/15 Tue
I/Adreno-EGL(  897): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  897): Remote Branch: 
I/Adreno-EGL(  897): Local Patches: 
I/Adreno-EGL(  897): Reconstruct Branch: 
,W/CAE     (  897): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  897): stop(ContextProvider.java:149)
,V/CAE     (  897): clear(AutoRotationRunner.java:182)
,V/CAE     (  897): disable(AutoRotationRunner.java:171)
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  897): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  897): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  897): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  897): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  897): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  897): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  897): removeSContextService() : service = Auto Rotation
D/SContextService(  897): ===== SContext Service List =====
D/SContextManager(  897):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@183cb1bb, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,I/CAE     (  897): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,D/InputMethodManagerService(  897): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  897):  handler : SCREEN_ON end
,D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NotificationService(  897): ACTION_SCREEN_ON
D/LightsService(  897): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  897): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/WifiStateMachine(  897): handleScreenStateChanged Exit: true
D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  897): Bridge Server is not available
,D/DisplayPowerController(  897): ColorFade: onAnimationStart
D/DisplayPowerController(  897): getFinalBrightness : 63 -> 0
,D/PersonaManagerService(  897): ACTION_SCREEN_ON onReceive
,D/lights  (  897): lcd : 12 +
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_ON called
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  897): do suspend false
,I/NfcService( 1468): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,I/wpa_supplicant( 1275): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1275): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1275): P2P: Current p2p state = IDLE
,D/lights  (  897): lcd : 12 -
,I/wpa_supplicant( 1275): Scan requested (ret=0) - scan timeout 30 seconds
,D/lights  (  897): lcd : 4 +
,D/NfcService( 1468): call the applyRotuiing
,D/lights  (  897): lcd : 4 -
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/DisplayPowerController(  897): getFinalBrightness : 63 -> 0
D/lights  (  897): lcd : 0 +
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 1952): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
D/accuweather( 1952): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,I/SamsungIME( 1821): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 1952): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/lights  (  897): lcd : 0 -
,D/SurfaceWidget.Renderer( 1952): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 1952): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 1952): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 1952): [237392/6] SurfaceWidget drawing first frame
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  1385 microsec. 
,I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7160): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 7160): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 897) 
,D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 70
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  897): unregisterListener ::   
D/lights  (  897): led_pattern : 1 +
,D/BatteryService(  897): turn on LED for charging
,D/SSRM:m  (  897): SIOP:: AP = 420, PST = 447, CUR = 300
,D/lights  (  897): led_pattern : 1 -
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  897): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 9, 19, 58,
D/SensorHubManager(  897): SendSensorHubData: send data = -63, 14, 9, 19, 58
,D/Sensorhubs(  297): sendContextData: -63, 14, 9, 19, 58
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1455031140000
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1455009599016
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
E/MotionRecognitionService(  897):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  897): handleScreenStateChanged Exit: false
D/NotificationService(  897): ACTION_SCREEN_OFF
D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x12 | SvcLED(id=4) set On
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 70
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  897): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  897): do suspend true
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  897): unregisterListener ::   
D/lights  (  897): led_pattern : 3 +
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,D/DisplayPowerState(  897): !@ ColorFade entry
D/lights  (  897): led_pattern : 3 -
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/DisplayPowerController(  897): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  897): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  897): unregisterListener ::   
,E/Sensors (  897): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  897): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/SensorManager(  897): unregisterListener ::   
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  897): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_OFF called
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  897): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/NfcService( 1468): call the applyRotuiing
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
V/ActivityManager(  897): Display changed displayId=0
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1952): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  73 microsec. 
I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7160): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7160): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  897): SIOP:: AP = 420, PST = 446, CUR = 300
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/PowerManagerService(  897): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceControl(  897): Excessive delay in setPowerMode(): 257ms
D/MISC PowerHAL(  897): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  897): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  897): Invalid hint ID.
I/QCOM PowerHAL(  897): Got set_interactive hint
,I/PowerManagerService(  897): [PWL] Off : 0s ago
,I/PowerManagerService(  897): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  897): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2365, ws=null) (elapsedTime=37833)
I/PowerManagerService(  897): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  897): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Display
,D/SSRM:a  (  897): DeviceInfo:: 000000000000,
,D/SSRM:a  (  897): SettingsAirViewInfo:: 000000000
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 2
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/wpa_supplicant( 1275): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService(  897): InactiveState{ what=147461 }
,D/WifiP2pService(  897): P2pEnabledState{ what=147461 }
,D/WifiP2pService(  897): DefaultState{ what=147461 }
,E/WifiStateMachine(  897): [1,455,009,602,637 ms] noteScanEnd no scan source
,E/WifiStateMachine(  897): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@e8ba4b1 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  897): External Intent Received android.net.wifi.SCAN_RESULTS
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 1.
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 897) 
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
,E/LightSensor(  897): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  897): turn on LED for fully charged
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService(  897): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169
,I/PowerManagerService(  897): !@[ps] Screen__On wl: PowerUI.Notification
,I/PowerManagerService(  897): Waking up from sleep (uid 10059)...
,V/KeyguardServiceDelegate(  897): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@db36e4a)
,D/KeyguardViewMediator( 1169): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1169): notifyScreenOnLocked
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  897): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  897): [s] UserActivityState : 0 -> 1
,D/PowerManagerService(  897): [PWL] sb acquire: PowerManagerService.Display
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/DisplayPowerController(  897): Blocking screen on until initial contents have been drawn.
,D/SContextService(  897): 	.registerCallback : 1, client=
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
,D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/AutomaticBrightnessController(  897): [DAB] updateAutoBrightnessSEC : 69(69.0)    1.0 < 70.0 < 203.0 (0.0)
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
D/PowerManagerService(  897): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  897): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  897): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 2
,I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 70
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
I/QCOM PowerHAL(  897): Got set_interactive hint
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6962000
D/DisplayPowerController(  897): getFinalBrightness : 69 -> 69
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
,W/CAE     (  897): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,I/CAE     (  897): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,I/CAE     (  897): setCAProperty(ContextAwareService.java:469) - result : true
W/CAE     (  897): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  897): sendProperty() : service = Auto Rotation
I/DisplayManagerService(  897): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/CAE     (  897): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  897): start(ContextProvider.java:126)
,V/CAE     (  897): clear(AutoRotationRunner.java:182)
,V/CAE     (  897): enable(AutoRotationRunner.java:158)
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -79, 7, 0, 0
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/PowerManagerService(  897): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 33ms
,E/Sensors (  897): Acc old sensor_state 8704, new sensor_state : 8705 en : 1
D/CAE     (  897): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  897): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/SensorManager(  897): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,D/PowerManagerService(  897): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 8ms
,D/DisplayPowerController(  897): getFinalBrightness : 69 -> 69
,D/KnoxNotification( 1169): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@e0345bd
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/CAE     (  897): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  897): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  897): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     (  897): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@2438a8e9, Service : AUTO_ROTATION(1)
,W/CAE     (  897): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  897): addSContextService() : service = Auto Rotation
D/SContextService(  897): ===== SContext Service List =====
,D/SContextService(  897): Listener : android.hardware.scontext.SContextService$Listener@3ccd196e, Service : Auto Rotation
D/SContextManager(  897):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@183cb1bb, service=Auto Rotation
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/InputManager-JNI(  897): setDeviceInteractive: 1
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/KeyguardViewMediator( 1169): handleNotifyScreenOn
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event2/device/enabled: 1
D/StatusBarKeyguardViewManager( 1169): onScreenTurnedOn()
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 71
,D/SensorManager(  897): unregisterListener ::   
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarKeyguardViewManager( 1169): callback.onShown()
V/KeyguardServiceDelegate(  897): **** SHOWN CALLED ****
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/DisplayPowerController(  897): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController(  897): Unblocked screen on after 159 ms
D/LockPatternUtilsCache( 1169): value : false
D/DisplayPowerState(  897): !@ ColorFade exit
,D/SamsungIME( 1821): showDlgMsgBox : false true true
,D/NfcService( 1468): call the applyRotuiing
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (8/8)
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (-2/8)
E/libEGL  (  897): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  897): getFinalBrightness : 69 -> 69
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/UserPresentBroadcastReceiver( 2069): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 89
,D/BatteryMeterView( 1169): onDraw batteryColor : -1
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 89
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 89
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3795): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3795): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  897): post active user change for 0
,D/KnoxTimeoutHandler(  897): postActiveUserChange for user 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
D/SurfaceControl(  897): Excessive delay in setPowerMode(): 290ms
D/lights  (  897): lcd : 69 +
,D/lights  (  897): lcd : 69 -
D/DisplayPowerController(  897): getFinalBrightness : 69 -> 69
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  897): SecHardwareInterface.setBatteryADC : true
D/lights  (  897): button : 1 +
D/PowerManagerService(  897): [input device light] setInputDeviceLightOn is called : 1
D/lights  (  897): button : 1 -
D/PowerManagerService(  897): [input device light] handleInputDeviceLightOn
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 3795): Timeline: Activity_idle id: android.os.BinderProxy@358cd0bb time:77557
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,V/ActivityManager(  897): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/ActivityManager(  897): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PalmMotion(  897): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotion(  897): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  897): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 71
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  897): unregisterListener ::   
D/lights  (  897): led_pattern : 5 +
D/SSRM:a  (  897): DeviceInfo:: 000000000000
D/SSRM:a  (  897): SettingsAirViewInfo:: 000000000
,D/KnoxTimeoutHandler(  897): handleActiveUserChange for user 0
,D/SLocation(  897): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,W/System.err(  897): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  897): 	at java.lang.Thread.run(Thread.java:818)
,D/LightsService(  897): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 897) 
,D/lights  (  897): led_pattern : 5 -
,D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
,D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  897): turn off LED
,I/CAE     (  897): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,D/LightsService(  897): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  (  897): led_pattern : 0 +
,D/lights  (  897): led_pattern : 0 -
D/InputMethodManagerService(  897): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/MotionRecognitionService(  897):  handler : SCREEN_ON end
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  897): handleScreenStateChanged Exit: true
,D/NotificationService(  897): ACTION_SCREEN_ON
D/LightsService(  897): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  897): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  897): do suspend false
D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  897): Bridge Server is not available
,I/wpa_supplicant( 1275): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1275): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1275): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1275): Scan requested (ret=0) - scan timeout 30 seconds
,D/PersonaManagerService(  897): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1468): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1468): call the applyRotuiing
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1952): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
D/accuweather( 1952): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
D/accuweather( 1952): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 1952): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
I/SamsungIME( 1821): getNextShiftState() cursorCapsMode : 0
,D/SurfaceWidget.Renderer( 1952): [237392/6] SurfaceWidget drawing first frame
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  234 microsec. 
,I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7160): [#DCM#] onReceive action = EVENT_SCREEN_ON
,I/DCMController( 7160): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Broadcasts
,D/SurfaceWidget.Renderer( 1952): [237392/6] SurfaceWidget drawing first frame
,D/SSRM:m  (  897): SIOP:: AP = 410, PST = 444, CUR = 300
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1455031140000
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1455009604633
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:a  (  897): DeviceInfo:: 000000000000
,D/SSRM:a  (  897): SettingsAirViewInfo:: 000000000
,D/PowerManagerService(  897): [input device light] handleInputDeviceLightOff
,D/lights  (  897): button : 0 +
,D/lights  (  897): button : 0 -
,E/SMD     (  286): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1275): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService(  897): InactiveState{ what=147461 }
,D/WifiP2pService(  897): P2pEnabledState{ what=147461 }
,D/WifiP2pService(  897): DefaultState{ what=147461 }
,E/WifiStateMachine(  897): [1,455,009,608,204 ms] noteScanEnd no scan source
,E/WifiStateMachine(  897): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@e8ba4b1 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  897): External Intent Received android.net.wifi.SCAN_RESULTS
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  286): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/SSRM:m  (  897): SIOP:: AP = 380, PST = 439, CUR = 300
,E/SMD     (  286): DCD ON
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  897): waitForAlarm result :4,
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7342): MountEmulatedStorage()
,E/Zygote  ( 7342): v2
I/libpersona( 7342): KNOX_SDCARD checking this for 10082
I/libpersona( 7342): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7342 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,I/SELinux ( 7342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,E/SELinux ( 7342): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3221): Disconnected process message: 10
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7342): TimaSignature is unavailable
,D/ActivityThread( 7342): Added TimaKeyStore provider
,D/ResourcesManager( 7342): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ReaderUtils( 7342): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,W/GAV2    ( 7342): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7342): Created application version: 3.3.11 (30311)
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 17710(992KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 780us total 35.381ms
,D/ResourcesManager( 2365): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7342): Starting books sync, d
,E/SQLiteLog( 7342): (284) automatic index on view_volumes(volume_id)
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SMD     (  286): DCD ON
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at dsf.a(PG:807)
E/HttpOperation( 6568): 	at fhk.a(PG:1126)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 8 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 10 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7342): null auth token
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/System.out( 7342): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 7342): (HTTPLog)-Static: isShipBuild true
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/System.out( 7342): (HTTPLog)-Thread-1213-1054476074: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6568): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at ieo.a(PG:43)
E/HttpOperation( 6568): 	at iep.a(PG:93)
E/HttpOperation( 6568): 	at fhn.a(PG:59)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/ExperimentLoader( 6568): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): 	at kfv.a(PG:65)
E/ExperimentLoader( 6568): 	at kff.u(PG:385)
E/ExperimentLoader( 6568): 	at kfb.a(PG:29)
E/ExperimentLoader( 6568): 	at kff.l(PG:132)
E/ExperimentLoader( 6568): 	at ieo.a(PG:43)
E/ExperimentLoader( 6568): 	at iep.a(PG:93)
E/ExperimentLoader( 6568): 	at fhn.a(PG:59)
E/ExperimentLoader( 6568): 	at lex.a(PG:85)
E/ExperimentLoader( 6568): 	at lex.b(PG:132)
E/ExperimentLoader( 6568): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6568): 	at fhk.a(PG:908)
E/ExperimentLoader( 6568): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6568): 	at ihi.a(PG:22)
E/ExperimentLoader( 6568): 	at kft.a(PG:91)
E/ExperimentLoader( 6568): 	at kfv.a(PG:62)
E/ExperimentLoader( 6568): 	... 12 more
E/ExperimentLoader( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6568): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6568): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6568): 	at ihi.a(PG:19)
E/ExperimentLoader( 6568): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6568): [getaccountstatus] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at ixd.a(PG:248)
E/HttpOperation( 6568): 	at ixd.b(PG:206)
E/HttpOperation( 6568): 	at ixd.a(PG:175)
E/HttpOperation( 6568): 	at fig.a(PG:78)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/EsSyncAdapterService( 6568): Sync failure
E/EsSyncAdapterService( 6568): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6568): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6568): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6568): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6568): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6568): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6568): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6568): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6568): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6568): 	... 10 more
E/EsSyncAdapterService( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6568): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6568): 	... 12 more
E/EsSyncAdapterService( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6568): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6568): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6568): 	... 14 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 62212, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5544404546396013354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 63815(3MB) AllocSpace objects, 19(564KB) LOS objects, 30% free, 36MB/52MB, paused 1.499ms total 83.698ms
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7342): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5544404546396013354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7342): null auth token
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5544404546396013354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/BooksSync( 7342): Soft error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5544404546396013354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7342): Sync error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5544404546396013354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7342): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62572, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  897): Killing 4908:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,W/libprocessgroup(  897): failed to open /acct/uid_10046/pid_4908/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,I/GAV2    ( 7342): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  897): waitForAlarm result :4
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7411): MountEmulatedStorage()
E/Zygote  ( 7411): v2
I/libpersona( 7411): KNOX_SDCARD checking this for 10179
I/libpersona( 7411): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7411 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 7411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7411): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7411): TimaSignature is unavailable
,D/ActivityThread( 7411): Added TimaKeyStore provider
,D/ResourcesManager( 7411): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 7411): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/UMC:Core( 7411): onCreate(): 
,D/USER_AGENT( 7411): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7411): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7411): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7411): ================================================
,I/CSTORAGE( 7411):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7411): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7411): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7411): FINISHED: initialize rv:0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 2.
,D/UMC:SecurityUtils( 7411): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7411): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7411): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7411): New Flow
,D/TimaService(  897): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService(  897): TIMA: in getTimaVersion
I/        (  897): CCM JNI: In ccm_register_for_default_cert
I/        (  897): CCM JNI: In ccm_create_slot
,I/TZ_CCM_C_Initialize: (  897): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  897): pInitArgs 0xaeef5814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  897): &ctx = 0x9feb2c1c
I/TLC_TZ_CCM: (  897): creating new ccm context...
I/TLC_TZ_CCM: (  897): initializing ccm context...
I/TLC_TZ_CCM: (  897): root = /firmware/image, root_strlen = 15
,I/TLC_TZ_CCM: (  897): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  897): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  897): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  897): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  897): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  897): aligned max_sendmsg_size = 19456
,I/TZ: client_server_communication(  897): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  897): Client_Server_Open was called
I/TZ: client_server_communication(  897): IClientServer::IClientServer()
I/TZ: client_server_communication(  897): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  897): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1076): OPENSWCONN
I/TZ_CCM_SERVER( 1076): creating new ccm context...
I/TZ_CCM_SERVER( 1076): initializing ccm context...
I/TZ_CCM_SERVER( 1076): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1076): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1076): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1076): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1076): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1076): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1076): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1076): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1076): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1076): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication( 1076): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  897): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  897): Client_Server_Open succeeded, serverName = CCM
,I/TZ_CCM_C_Initialize: (  897): ctx = 0x949ff6c0, comm = 0x928e5b20, sendmsg = 0x949e6000, recvmsg = 0x949eac00
I/TZ_init: (  897): TZ_init: sending initialization request...
I/TZ: client_server_communication(  897): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  897): Calling Communicate()
,I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1076): COMM
,I/TZ_init: (  897): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: (  897): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  897): Cmd id = 17, len = 19456
,I/TZ: client_server_communication(  897): Calling Communicate()
,I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1076): COMM
,I/TZ_COMMON: tlc_key_db_util: (  897): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  897): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  897): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  897): Calling Communicate()
,I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
,I/TZ_CCM_SERVER( 1076): COMM
,I/TLC_TZ_CCM: register for default cert: (  897): TZ_CCM_register_default_TLC_END: DB file size to update is 0
,I/TLC_TZ_CCM: register for default cert: (  897): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  897): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
,I/TZ: client_server_communication(  897): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  897): Calling Communicate()
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
,I/TZ_CCM_SERVER( 1076): COMM
I/TZ: client_server_communication(  897): Client_Server_Close was called
,I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(1) 16
,I/TZ_CCM_SERVER( 1076): CLOSESWCONN
D/QSEECOMAPI: ( 1076): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1076): QSEECom_shutdown_app, app_id = 2
,I/TZ: client_server_communication(  897): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7411): ccmRegisterForDefaultCertificate: 0
,D/UMC:CloudMDMSecurity( 7411): TIMA service call for password change success!!
,D/UMC:AdminManager( 7411): init - start
,D/UMC:AdminManager( 7411): loadAdmins
,D/UMC:AdminManager( 7411): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7411): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7411): init - end
,V/UMC:AlarmHandler( 7411): Enter loadList
,D/GSLBManager( 7411): migrateStoredUrlFromOldPref
,D/GSLBManager( 7411): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7411): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7411): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7411): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7411): isContainer : 0
,W/LicenseLogService(  897): log() failed
,D/EnterpriseDeviceManagerService(  897): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7411): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7411): isContainer : 0
,D/UMC:UMCAdmin( 7411): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7411): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,D/QuickStartReceiver( 7411): Msg Id : 2
D/QuickStartReceiver( 7411): model : SM-G900F
D/QuickStartReceiver( 7411): id : 100
,I/ActivityManager(  897): Killing 5892:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_10158/pid_5892/cgroup.procs: No such file or directory
,D/PowerManagerService(  897): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 360, PST = 432, CUR = 300
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PowerManagerService(  897): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  897): lcd : 60 +
,D/lights  (  897): lcd : 60 -
,D/lights  (  897): lcd : 52 +
,D/lights  (  897): lcd : 52 -
,D/lights  (  897): lcd : 43 +
,D/lights  (  897): lcd : 43 -
,D/lights  (  897): lcd : 35 +
,D/lights  (  897): lcd : 35 -
,D/lights  (  897): lcd : 27 +
,D/lights  (  897): lcd : 27 -
,D/lights  (  897): lcd : 18 +
,D/lights  (  897): lcd : 18 -
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,D/lights  (  897): lcd : 15 +
,D/lights  (  897): lcd : 15 -
,D/DisplayPowerController(  897): getFinalBrightness : 15 -> 15
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/Watchdog(  897): !@Sync 3
,E/SMD     (  286): DCD ON
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/SMD     (  286): DCD ON
,D/PackageManager(  897): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  897): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,I/UpdateIcingCorporaServi( 1553): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  ( 7451): MountEmulatedStorage()
E/Zygote  ( 7451): v2
I/libpersona( 7451): KNOX_SDCARD checking this for 10075
I/libpersona( 7451): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7451 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/SELinux ( 7451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 7451): TimaSignature is unavailable
,D/ActivityThread( 7451): Added TimaKeyStore provider
,D/ResourcesManager( 7451): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 7451): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7466): MountEmulatedStorage()
E/Zygote  ( 7466): v2
I/libpersona( 7466): KNOX_SDCARD checking this for 1000
I/libpersona( 7466): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7466 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1553): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,I/ActivityManager(  897): Killing 5875:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,I/art     (  312): Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 12.170ms
,D/BackupManagerService(  897): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.610ms
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux ( 7466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.982ms
I/SELinux ( 7466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5875/cgroup.procs: No such file or directory
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/TimaKeyStoreProvider( 7466): TimaSignature is unavailable
,D/ActivityThread( 7466): Added TimaKeyStore provider
,D/PowerManagerService(  897): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  897): Nap time (uid 1000)...
I/PowerManagerService(  897): !@[ps] Screen__Off(2) : 
D/InputManager-JNI(  897): setDeviceInteractive: 0
I/PowerManagerService(  897): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  897): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  897): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService(  897): handleSandman : startDream()
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  897): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  897): Sleeping (uid 1000)...,
D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  897): [s] UserActivityState : 4 -> 0
D/SContextService(  897): 	.unregisterCallback : 1, client=
D/PowerManagerService(  897): [input device light] setInputDeviceLightOn is called : 0
D/SContextService(  897): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3ccd196e, Service = Auto Rotation, used = 1
D/PowerManagerService(  897): [input device light] handleInputDeviceLightOff
I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),2 flag=404, ColorFade
,W/CAE     (  897): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  897): stop(ContextProvider.java:149)
,V/CAE     (  897): clear(AutoRotationRunner.java:182)
,V/CAE     (  897): disable(AutoRotationRunner.java:171)
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SensorHubManager(  897): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/ResourcesManager( 7466): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,W/ResourcesManager( 7466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CAE     (  897): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  897): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/CAE     (  897): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  897): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  897): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  897): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  897): removeSContextService() : service = Auto Rotation
D/SContextService(  897): ===== SContext Service List =====
D/SContextManager(  897):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@183cb1bb, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
,E/Zygote  ( 7484): MountEmulatedStorage()
E/Zygote  ( 7484): v2
I/libpersona( 7484): KNOX_SDCARD checking this for 1000
I/libpersona( 7484): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ActivityManager(  897): Killing 6254:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/SELinux ( 7484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  897): ColorFade: onAnimationStart
D/DisplayPowerController(  897): getFinalBrightness : 69 -> 0
,D/lights  (  897): lcd : 13 +
,D/TimaKeyStoreProvider( 7484): TimaSignature is unavailable
,D/ActivityThread( 7484): Added TimaKeyStore provider
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/lights  (  897): lcd : 13 -
D/lights  (  897): lcd : 5 +
,D/DisplayPowerController(  897): getFinalBrightness : 69 -> 0
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/lights  (  897): lcd : 5 -
D/lights  (  897): lcd : 0 +
,D/lights  (  897): lcd : 0 -
,W/libprocessgroup(  897): failed to open /acct/uid_10168/pid_6254/cgroup.procs: No such file or directory
W/ResourcesManager( 6459): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 7484): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
W/ResourcesManager( 6459): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 897) 
,D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 74
,W/ResourcesManager( 6459): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  897): unregisterListener ::   
D/lights  (  897): led_pattern : 5 +
,D/lights  (  897): led_pattern : 5 -
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  897): turn on LED for fully charged
,I/CAE     (  897): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 9, 20, 34,
D/SensorHubManager(  897): SendSensorHubData: send data = -63, 14, 9, 20, 34
,D/Sensorhubs(  297): sendContextData: -63, 14, 9, 20, 34
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_OFF
,W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ShortcutReceiver( 7484):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/MotionRecognitionService(  897):  handler : SCREEN_OFF end 
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  897): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  897): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  897): do suspend true
D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/DisplayPowerState(  897): !@ ColorFade entry
,D/DisplayPowerController(  897): ColorFade: onAnimationEnd
,W/ResourcesManager( 6459): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/NotificationService(  897): ACTION_SCREEN_OFF
,D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 897) 
,D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 73
,D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  897): unregisterListener ::   
,E/Sensors (  897): Acc old sensor_state 8705, new sensor_state : 8704 en : 0
,I/ActivityManager(  897): Killing 6746:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/LightSensor(  897): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SensorManager(  897): unregisterListener ::   
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,W/ResourcesManager( 6459): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/SensorManager(  897): unregisterListener ::   
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  897): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/ActivityManager(  897): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PackageBroadcastService( 2365): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,I/PeopleContactsSync( 2365): CP2 sync disabled
D/ResourcesManager( 6459): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/libprocessgroup(  897): failed to open /acct/uid_10015/pid_6746/cgroup.procs: No such file or directory
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  897): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/ResourcesManager( 6459): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 6459): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/PersonaManagerService(  897): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1468): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 1952): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  550 microsec. 
,I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7160): [#DCM#] onReceive action = EVENT_SCREEN_OFF
,I/DCMController( 7160): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  897): SIOP:: AP = 340, PST = 423, CUR = 300
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  897): Excessive delay in setPowerMode(): 276ms
,D/PowerManagerService(  897): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  897): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL(  897): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  897): Got set_interactive hint
,I/PowerManagerService(  897): [PWL] Off : 0s ago
,I/PowerManagerService(  897): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  897): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryService(  897): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 5s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/FactoryTest( 6703): Not factory mode
,D/FactoryTest( 6703): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6703): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6703): still no open session command from host, so toast
,W/ContextImpl( 6703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6703): Timeline: Activity_launch_request id:com.android.settings time:116324
,E/PersonaManagerService(  897): inState():  stateMachine is null !!
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  897): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  897): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6703): started activity for popup
,I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6703): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6703): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6703): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  897): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  897): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1daaefbe attribute=android.view.inputmethod.EditorInfo@21c8281f, token = android.os.BinderProxy@f4a2ecd
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/AlarmManager(  897): waitForAlarm result :4
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6703): dev.kiessupport is : TRUE
,D/Activity( 6703): performCreate Call secproduct feature valuefalse
,D/Activity( 6703): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 89
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 89
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 89
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3795): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3795): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  897): post active user change for 0
,D/KnoxTimeoutHandler(  897): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  897): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DBG_DM  ( 3795): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/Timeline( 3795): Timeline: Activity_idle id: android.os.BinderProxy@358cd0bb time:116788
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 3.
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  897): SIOP:: AP = 340, PST = 410, CUR = 300
,E/SMD     (  286): DCD ON
,W/ActivityManager(  897): mDVFSHelper.release()
,D/TaskPersister(  897): removeObsoleteFile: deleting file=17_task.xml
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 15s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  897): SIOP:: AP = 330, PST = 395, CUR = 300
,D/X       (  897): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1221):  LEVEL : -1
,E/Zygote  ( 7545): MountEmulatedStorage()
,E/Zygote  ( 7545): v2
I/libpersona( 7545): KNOX_SDCARD checking this for 10054
,I/libpersona( 7545): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7545 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 7545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SystemBroadcastReceiver( 7160): [#DCM#] [DCM_Performance] onReceive completed in time  1606 microsec. 
,E/SELinux ( 7545): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SystemBroadcastReceiver( 7160): [#DCM#] Calling notifyListeners. 
,D/TimaKeyStoreProvider( 7545): TimaSignature is unavailable
,D/ActivityThread( 7545): Added TimaKeyStore provider
,I/DCMPolicyManager( 7160): [#DCM#] onReceive action = EVENT_SIOP
,D/ResourcesManager( 7545): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7545): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7545): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7545): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7545): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7545): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 7545): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7545): core_num = 4
,W/linker  ( 7545): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7545): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7545): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 7545): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7545):  SIOP_LEVEL: -1,
,I/ActivityManager(  897): Killing 6767:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_10016/pid_6767/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,I/PowerManagerService(  897): [PWL] Off : 30s ago
,I/PowerManagerService(  897): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  897): [PWL]     mWakeLockSummary : 0x1
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  897): SIOP:: AP = 320, PST = 378, CUR = 300
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON,
,D/SSRM:m  (  897): SIOP:: AP = 320, PST = 364, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7342): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9144052777849910674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 50s ago
I/PowerManagerService(  897): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  897): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=897, ws=WorkSource{10082}) (elapsedTime=735)
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 353, CUR = 300
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,V/AlarmManager(  897): waitForAlarm result :4
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9144052777849910674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/art     (  897): Explicit concurrent mark sweep GC freed 70064(3MB) AllocSpace objects, 31(756KB) LOS objects, 30% free, 36MB/52MB, paused 1.809ms total 310.636ms
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9144052777849910674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/BooksSync( 7342): Soft error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9144052777849910674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7342): Sync error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9144052777849910674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7342): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 156997, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 35491(2MB) AllocSpace objects, 20(1620KB) LOS objects, 40% free, 17MB/29MB, paused 677us total 48.583ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at dsf.a(PG:807)
E/HttpOperation( 6568): 	at fhk.a(PG:1126)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 8 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 10 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6568): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at ieo.a(PG:43)
E/HttpOperation( 6568): 	at iep.a(PG:93)
E/HttpOperation( 6568): 	at fhn.a(PG:59)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/ExperimentLoader( 6568): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): 	at kfv.a(PG:65)
E/ExperimentLoader( 6568): 	at kff.u(PG:385)
E/ExperimentLoader( 6568): 	at kfb.a(PG:29)
E/ExperimentLoader( 6568): 	at kff.l(PG:132)
E/ExperimentLoader( 6568): 	at ieo.a(PG:43)
E/ExperimentLoader( 6568): 	at iep.a(PG:93)
E/ExperimentLoader( 6568): 	at fhn.a(PG:59)
E/ExperimentLoader( 6568): 	at lex.a(PG:85)
E/ExperimentLoader( 6568): 	at lex.b(PG:132)
E/ExperimentLoader( 6568): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6568): 	at fhk.a(PG:908)
E/ExperimentLoader( 6568): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6568): 	at ihi.a(PG:22)
E/ExperimentLoader( 6568): 	at kft.a(PG:91)
E/ExperimentLoader( 6568): 	at kfv.a(PG:62)
E/ExperimentLoader( 6568): 	... 12 more
E/ExperimentLoader( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6568): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6568): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6568): 	at ihi.a(PG:19)
E/ExperimentLoader( 6568): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
E/HttpOperation( 6568): [getaccountstatus] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at ixd.a(PG:248)
E/HttpOperation( 6568): 	at ixd.b(PG:206)
E/HttpOperation( 6568): 	at ixd.a(PG:175)
E/HttpOperation( 6568): 	at fig.a(PG:78)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
E/EsSyncAdapterService( 6568): Sync failure
E/EsSyncAdapterService( 6568): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6568): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6568): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6568): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6568): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6568): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6568): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6568): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6568): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6568): 	... 10 more
E/EsSyncAdapterService( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6568): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6568): 	... 12 more
E/EsSyncAdapterService( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6568): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6568): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6568): 	... 14 more
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 157456, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  897): !@Sync 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 342, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 332, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1674): Vacuum at: now=1455009706366 tag=VacuumService
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1674): Using platform SSLCertificateSocketFactory
,W/Uploader( 1674): No account for auth token provided
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1674): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1674): (HTTPLog)-Static: isShipBuild true
I/System.out( 1674): (HTTPLog)-Thread-198-889878093: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1674): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,I/qtaguid ( 1674): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1674): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1674): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 1674): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
D/PanelView( 1169): There is/are notification(s) 
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674):  no longer exists, so no auth token.
,I/qtaguid ( 1674): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 75s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 325, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 6
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 319, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 315, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  897): [PWL] Off : 105s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 311, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/Watchdog(  897): !@Sync 7
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 308, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 140s ago
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 304, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  897): !@Sync 8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 302, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 9
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7342): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7147028243447332674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7147028243447332674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7147028243447332674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  897): [PWL] Off : 180s ago
,I/PowerManagerService(  897): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  897): [PWL]     mWakeLockSummary : 0x1,
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=897, ws=WorkSource{10082}) (elapsedTime=3272),
,E/BooksSync( 7342): Soft error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7147028243447332674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7342): Sync error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7147028243447332674&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7342): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284342, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 51370(2MB) AllocSpace objects, 46(1256KB) LOS objects, 30% free, 36MB/52MB, paused 1.622ms total 131.129ms
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  286): DCD ON,
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  286): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  897): initializing...
,I/TLC_TIMA_PKM_initialize(  897): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  897): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  897): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  897): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  897): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  897): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  897): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  897): QSEECom_get_handle sb_length = 0x80080,
,D/QSEECOMAPI: (  897): App is not loaded in QSEE
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/QSEECOMAPI: (  897): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  897): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  897): Trustlet response is completed
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 10
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at dsf.a(PG:807)
E/HttpOperation( 6568): 	at fhk.a(PG:1126)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 8 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 10 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6568): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at ieo.a(PG:43)
E/HttpOperation( 6568): 	at iep.a(PG:93)
E/HttpOperation( 6568): 	at fhn.a(PG:59)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/ExperimentLoader( 6568): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): 	at kfv.a(PG:65)
E/ExperimentLoader( 6568): 	at kff.u(PG:385)
E/ExperimentLoader( 6568): 	at kfb.a(PG:29)
E/ExperimentLoader( 6568): 	at kff.l(PG:132)
E/ExperimentLoader( 6568): 	at ieo.a(PG:43)
E/ExperimentLoader( 6568): 	at iep.a(PG:93)
E/ExperimentLoader( 6568): 	at fhn.a(PG:59)
E/ExperimentLoader( 6568): 	at lex.a(PG:85)
E/ExperimentLoader( 6568): 	at lex.b(PG:132)
E/ExperimentLoader( 6568): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6568): 	at fhk.a(PG:908)
E/ExperimentLoader( 6568): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6568): 	at ihi.a(PG:22)
E/ExperimentLoader( 6568): 	at kft.a(PG:91)
E/ExperimentLoader( 6568): 	at kfv.a(PG:62)
E/ExperimentLoader( 6568): 	... 12 more
E/ExperimentLoader( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6568): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6568): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6568): 	at ihi.a(PG:19)
E/ExperimentLoader( 6568): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [getaccountstatus] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at ixd.a(PG:248)
E/HttpOperation( 6568): 	at ixd.b(PG:206)
E/HttpOperation( 6568): 	at ixd.a(PG:175)
E/HttpOperation( 6568): 	at fig.a(PG:78)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/EsSyncAdapterService( 6568): Sync failure
E/EsSyncAdapterService( 6568): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6568): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6568): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6568): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6568): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6568): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6568): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6568): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6568): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6568): 	... 10 more
E/EsSyncAdapterService( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6568): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6568): 	... 12 more
E/EsSyncAdapterService( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6568): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6568): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6568): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 293157, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 299, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 299, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  897): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7738 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7738): MountEmulatedStorage()
,E/Zygote  ( 7738): v2
I/libpersona( 7738): KNOX_SDCARD checking this for 10081
I/libpersona( 7738): KNOX_SDCARD not a persona
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,I/SELinux ( 7738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7738): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7738): TimaSignature is unavailable
,D/ActivityThread( 7738): Added TimaKeyStore provider
,D/ResourcesManager( 7738): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  897): Killing 6788:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6788/cgroup.procs: No such file or directory
,I/PowerManagerService(  897): [PWL] Off : 225s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 298, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  897): !@Sync 11
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/SMD     (  286): DCD ON
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/PlayEventLogger( 6597): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6597): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6597): Ignoring header User-Agent because its value was null.
,I/System.out( 6597): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6597): (HTTPLog)-Static: isShipBuild true
I/System.out( 6597): (HTTPLog)-Thread-1083-539773624: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 12
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 275s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true,
D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 293, CUR = 300
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 13
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 292, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  897): !@Sync 14
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  897): [PWL] Off : 330s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  897): !@Sync 15
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/SMD     (  286): DCD ON
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/bootchecker(  318): bootchecker wake up!!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  897): !@Sync 16
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  897): [PWL] Off : 390s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 17
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  897): waitForAlarm result :4
,E/SMD     (  286): DCD ON
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7342): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7342): null auth token
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8069721470206515393&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 48651(2MB) AllocSpace objects, 67(4MB) LOS objects, 39% free, 18MB/30MB, paused 685us total 55.897ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
I/qtaguid ( 7342): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8069721470206515393&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,E/SMD     (  286): DCD ON
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8069721470206515393&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7342): Soft error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8069721470206515393&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7342): Sync error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8069721470206515393&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7342): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 535624, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 18
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 455s ago
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Daemon(  325): Stop the daemon....
,E/Watchdog(  897): !@Sync 19
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at dsf.a(PG:807)
E/HttpOperation( 6568): 	at fhk.a(PG:1126)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 8 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 10 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at ieo.a(PG:43)
E/HttpOperation( 6568): 	at iep.a(PG:93)
E/HttpOperation( 6568): 	at fhn.a(PG:59)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/ExperimentLoader( 6568): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): 	at kfv.a(PG:65)
E/ExperimentLoader( 6568): 	at kff.u(PG:385)
E/ExperimentLoader( 6568): 	at kfb.a(PG:29)
E/ExperimentLoader( 6568): 	at kff.l(PG:132)
E/ExperimentLoader( 6568): 	at ieo.a(PG:43)
E/ExperimentLoader( 6568): 	at iep.a(PG:93)
E/ExperimentLoader( 6568): 	at fhn.a(PG:59)
E/ExperimentLoader( 6568): 	at lex.a(PG:85)
E/ExperimentLoader( 6568): 	at lex.b(PG:132)
E/ExperimentLoader( 6568): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6568): 	at fhk.a(PG:908)
E/ExperimentLoader( 6568): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6568): 	at ihi.a(PG:22)
E/ExperimentLoader( 6568): 	at kft.a(PG:91)
E/ExperimentLoader( 6568): 	at kfv.a(PG:62)
E/ExperimentLoader( 6568): 	... 12 more
E/ExperimentLoader( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6568): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6568): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6568): 	at ihi.a(PG:19)
E/ExperimentLoader( 6568): 	... 14 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [getaccountstatus] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at ixd.a(PG:248)
E/HttpOperation( 6568): 	at ixd.b(PG:206)
E/HttpOperation( 6568): 	at ixd.a(PG:175)
E/HttpOperation( 6568): 	at fig.a(PG:78)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/EsSyncAdapterService( 6568): Sync failure
E/EsSyncAdapterService( 6568): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6568): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6568): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6568): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6568): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6568): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6568): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6568): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6568): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6568): 	... 10 more
E/EsSyncAdapterService( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6568): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6568): 	... 12 more
E/EsSyncAdapterService( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6568): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6568): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6568): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 578596, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2825): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     (  897): Explicit concurrent mark sweep GC freed 59636(4MB) AllocSpace objects, 108(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.489ms total 113.623ms
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 20
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 525s ago
,I/ActivityManager(  897): Killing 6803:com.policydm/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6803/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 21
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 22
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 23
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,I/PowerManagerService(  897): [PWL] Off : 600s ago
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 24
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 25
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 680s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 26
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 27
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 28
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  897): [PWL] Off : 765s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 29
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 30
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/Finsky  ( 6597): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/LightsService(  897): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,E/LightSensor(  897): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  ,
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/GCM     ( 1674): Message class com.google.f.a.a.i
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 81
,E/LightSensor(  897): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  897): unregisterListener ::   
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,W/Finsky  ( 6597): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6597): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6597): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6597): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6597): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6597): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 2069): client connected with version: 7571000
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 31
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  897): [PWL] Off : 855s ago
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager(  897): waitForAlarm result :8
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  897): !@Sync 32
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 33
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 34
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7342): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,V/AlarmManager(  897): waitForAlarm result :4
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3102038007007605886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 51948(4MB) AllocSpace objects, 134(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.243ms total 98.765ms
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 40383(2MB) AllocSpace objects, 14(1134KB) LOS objects, 39% free, 18MB/30MB, paused 1.148ms total 45.472ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3102038007007605886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  286): DCD ON
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7342): Authentication error
E/BooksAccountManager( 7342): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7342): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7342): null auth token
,I/qtaguid ( 7342): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7342, getuid(): 10082
,I/qtaguid ( 7342): Untagging socket 34
,W/ApiaryClient( 7342): Error response from books API: {
W/ApiaryClient( 7342):  "error": {
W/ApiaryClient( 7342):   "errors": [
W/ApiaryClient( 7342):    {
W/ApiaryClient( 7342):     "domain": "global",
W/ApiaryClient( 7342):     "reason": "required",
W/ApiaryClient( 7342):     "message": "Login Required",
W/ApiaryClient( 7342):     "locationType": "header",
W/ApiaryClient( 7342):     "location": "Authorization"
W/ApiaryClient( 7342):    }
W/ApiaryClient( 7342):   ],
W/ApiaryClient( 7342):   "code": 401,
W/ApiaryClient( 7342):   "message": "Login Required"
W/ApiaryClient( 7342):  }
W/ApiaryClient( 7342): }
,W/ApiaryClient( 7342): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3102038007007605886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7342): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7342): Soft error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3102038007007605886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7342): Sync error
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7342): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3102038007007605886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7342): Headers suppressed
E/BooksSync( 7342): 
E/BooksSync( 7342): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7342): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1033784, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2825): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2825): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  897): stay LED for fully charged
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6597): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6597): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6597): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 950s ago
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 35
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 36
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6568): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at dsf.a(PG:807)
E/HttpOperation( 6568): 	at fhk.a(PG:1126)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 8 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6568): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at kff.l(PG:132)
E/HttpOperation( 6568): 	at ieo.a(PG:43)
E/HttpOperation( 6568): 	at iep.a(PG:93)
E/HttpOperation( 6568): 	at fhn.a(PG:59)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/ExperimentLoader( 6568): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6568): 	at kfv.a(PG:65)
E/ExperimentLoader( 6568): 	at kff.u(PG:385)
E/ExperimentLoader( 6568): 	at kfb.a(PG:29)
E/ExperimentLoader( 6568): 	at kff.l(PG:132)
E/ExperimentLoader( 6568): 	at ieo.a(PG:43)
E/ExperimentLoader( 6568): 	at iep.a(PG:93)
E/ExperimentLoader( 6568): 	at fhn.a(PG:59)
E/ExperimentLoader( 6568): 	at lex.a(PG:85)
E/ExperimentLoader( 6568): 	at lex.b(PG:132)
E/ExperimentLoader( 6568): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6568): 	at fhk.a(PG:908)
E/ExperimentLoader( 6568): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6568): 	at ihi.a(PG:22)
E/ExperimentLoader( 6568): 	at kft.a(PG:91)
E/ExperimentLoader( 6568): 	at kfv.a(PG:62)
E/ExperimentLoader( 6568): 	... 12 more
E/ExperimentLoader( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6568): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6568): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6568): 	at ihi.a(PG:19)
E/ExperimentLoader( 6568): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Watchdog(  897): !@Sync 37
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6568): [getaccountstatus] Unexpected exception
E/HttpOperation( 6568): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6568): 	at kfv.a(PG:65)
E/HttpOperation( 6568): 	at kff.u(PG:385)
E/HttpOperation( 6568): 	at kfb.a(PG:29)
E/HttpOperation( 6568): 	at ixd.a(PG:248)
E/HttpOperation( 6568): 	at ixd.b(PG:206)
E/HttpOperation( 6568): 	at ixd.a(PG:175)
E/HttpOperation( 6568): 	at fig.a(PG:78)
E/HttpOperation( 6568): 	at lex.a(PG:85)
E/HttpOperation( 6568): 	at lex.b(PG:132)
E/HttpOperation( 6568): 	at fhk.a(PG:1146)
E/HttpOperation( 6568): 	at fhk.a(PG:908)
E/HttpOperation( 6568): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6568): 	at ihi.a(PG:22)
E/HttpOperation( 6568): 	at kft.a(PG:91)
E/HttpOperation( 6568): 	at kfv.a(PG:62)
E/HttpOperation( 6568): 	... 12 more
E/HttpOperation( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6568): 	at gde.c(Unknown Source)
E/HttpOperation( 6568): 	at gde.b(Unknown Source)
E/HttpOperation( 6568): 	at ihi.a(PG:19)
E/HttpOperation( 6568): 	... 14 more
,E/EsSyncAdapterService( 6568): Sync failure
E/EsSyncAdapterService( 6568): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6568): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6568): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6568): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6568): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6568): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6568): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6568): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6568): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6568): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6568): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6568): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6568): 	... 10 more
E/EsSyncAdapterService( 6568): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6568): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6568): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6568): 	... 12 more
E/EsSyncAdapterService( 6568): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6568): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6568): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6568): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6568): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1122614, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SMD     (  286): DCD ON
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  897): waitForAlarm result :8
,E/Watchdog(  897): !@Sync 38
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1050s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 39
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  897): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  897): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  897): Updating Usage Statistics in DB @ 1455010738285
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.o,s.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134),
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  897): Done Updating Usage Statistics in DB @ 1455010738591
,E/Watchdog(  897): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  897): !@Sync 41
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3221): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3221): Disconnected process message: 10
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SMD     (  286): DCD ON
D/AndroidRuntime( 8027): 
D/AndroidRuntime( 8027): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8027): CheckJNI is OFF
D/AndroidRuntime( 8027): setted country_code = Germany
D/AndroidRuntime( 8027): setted countryiso_code = DE
D/AndroidRuntime( 8027): setted sales_code = DBT
D/AndroidRuntime( 8027): readGMSProperty: start
D/AndroidRuntime( 8027): readGMSProperty: already setted!!
D/AndroidRuntime( 8027): readGMSProperty: end
D/AndroidRuntime( 8027): addProductProperty: start
I/PowerManagerService(  897): [PWL] Off : 1155s ago
E/AffinityControl( 8027): AffinityControl: registerfunction enter
D/AndroidRuntime( 8027): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  897): START PACKAGE DELETE: observer{848944411}
D/PackageManager(  897): pkg{<packageName>}
D/PackageManager(  897): user{0}
D/PackageManager(  897): caller{2000}
D/PackageManager(  897): flags{3}
D/PersonaManagerService(  897): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  897): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  897): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  897): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  897): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  897): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  897): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  897): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  897): getApplicationUninstallationEnabled
D/ApplicationPolicy(  897): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  897): !@killApplicatoin: 10200, uninstall pkg
I/ActivityManager(  897): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
I/ActivityManager(  897): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
I/art     ( 4582): Explicit concurrent mark sweep GC freed 4632(256KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 314us total 30.014ms
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  897): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
E/SamsungIME( 1821): mOCRHelper is null
W/GeofencerStateMachine( 2069): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/Zygote  ( 8053): MountEmulatedStorage()
I/libpersona( 8053): KNOX_SDCARD checking this for 10019
E/Zygote  ( 8053): v2
I/libpersona( 8053): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8053 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SELinux ( 8053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/art     ( 1553): Explicit concurrent mark sweep GC freed 60017(3MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 1.843ms total 124.624ms
E/SELinux ( 8053): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/TimaKeyStoreProvider( 8053): TimaSignature is unavailable
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ActivityThread( 8053): Added TimaKeyStore provider
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager( 8053): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/RegisteredServicesCache( 1468): empty dynamic service
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/KLMS-2.4.503: ( 8053): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.503: ( 8053): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1455010790437
I/KLMS-2.4.503: ( 8053): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/KLMS-2.4.503: ( 8053): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  897): PackageReceiver onReceive()
I/HarmonyEASService(  897): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/KnoxMUMContainerPolicy(  897): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  897): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  897): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  897): uID is 10200
V/EnterpriseBillingPolicy(  897): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - end - null
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8072): MountEmulatedStorage()
I/libpersona( 8072): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8072): v2
I/libpersona( 8072): KNOX_SDCARD not a persona
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/ActivityManager(  897): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8072 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  897): Killing 5217:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/SELinux ( 8072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService(  897): Package has changed for user 0
D/EnterpriseDeviceManagerService(  897): Admin package name: com.google.android.gms
D/TimaKeyStoreProvider( 8072): TimaSignature is unavailable
W/libprocessgroup(  897): failed to open /acct/uid_10038/pid_5217/cgroup.procs: No such file or directory
D/ActivityThread( 8072): Added TimaKeyStore provider
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 8072): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/art     (  897): Explicit concurrent mark sweep GC freed 65016(4MB) AllocSpace objects, 83(1653KB) LOS objects, 30% free, 37MB/53MB, paused 1.654ms total 284.880ms
D/elm:14451( 8072): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8072): ELMEngine.ELMEngine( context ).
D/elm:14451( 8072): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/elm:14451( 8072): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8072): ElmAgentService : onCreate()
D/elm:14451( 8072): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8072): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8072): MDMBridge.getInstance()
D/elm:14451( 8072): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8088): MountEmulatedStorage()
E/Zygote  ( 8088): v2
I/libpersona( 8088): KNOX_SDCARD checking this for 10017
I/libpersona( 8088): KNOX_SDCARD not a persona
D/elm:14451( 8072): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager(  897): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8088 uid=10017 gids={50017, 9997} abi=armeabi-v7a
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/PackageManager(  897): delete codoeFile: 
D/PackageManager(  897): result of delete: 1{848944411}
I/SELinux ( 8088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8072): ElmAgentService : onDestroy().
I/ActivityManager(  897): Killing 6057:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 8088): TimaSignature is unavailable
D/ActivityThread( 8088): Added TimaKeyStore provider
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/AndroidRuntime( 8027): Shutting down VM
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 8088): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8088): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8088): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8088): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
E/Zygote  ( 8104): MountEmulatedStorage()
E/Zygote  ( 8104): v2
I/libpersona( 8104): KNOX_SDCARD checking this for 1000
I/libpersona( 8104): KNOX_SDCARD not a persona
W/ResourcesManager(  897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/ActivityManager(  897): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  897): Killing 6823:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/SELinux ( 8104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8104): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  897): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  897): onPackageRemoved : com.test.thalitest
D/TimaKeyStoreProvider( 8104): TimaSignature is unavailable
D/ActivityThread( 8104): Added TimaKeyStore provider
W/libprocessgroup(  897): failed to open /acct/uid_10042/pid_6057/cgroup.procs: No such file or directory
D/ResourcesManager( 8104): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8104): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8104): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8104): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 8104): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8104): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8104): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8104): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  897): failed to open /acct/uid_10045/pid_6823/cgroup.procs: No such file or directory
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8119): MountEmulatedStorage()
I/libpersona( 8119): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8119): v2
I/libpersona( 8119): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=8119 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 8119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8119): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  897): Killing 5722:com.android.mms/u0a50 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 8119): TimaSignature is unavailable
D/ActivityThread( 8119): Added TimaKeyStore provider
D/CountryDetector(  897): No listener is left
D/ResourcesManager( 8119): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 8119): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8119): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 8119): PushLog.txt file is not deleted.
D/SPPClientService( 8119): PushLog.txt file is not deleted.
D/SPPClientService( 8119): ============PushLog. stop!
W/libprocessgroup(  897): failed to open /acct/uid_10050/pid_5722/cgroup.procs: No such file or directory
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8137): MountEmulatedStorage()
E/Zygote  ( 8137): v2
I/libpersona( 8137): KNOX_SDCARD checking this for 10038
I/libpersona( 8137): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8137 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  897): Killing 6844:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
I/SELinux ( 8137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8137): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  897): failed to open /acct/uid_10051/pid_6844/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8137): TimaSignature is unavailable
D/ActivityThread( 8137): Added TimaKeyStore provider
D/ResourcesManager( 8137): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 8137): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8137): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 8137): PushLog.txt file is not deleted.
D/SPPClientService( 8137): PushLog.txt file is not deleted.
D/SPPClientService( 8137): ============PushLog. stop!
E/SQLiteDatabase( 8137): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 8137): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8137): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8137): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8137): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8137): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8137): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 8137): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 8137): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 8137): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 8137): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 8137): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 8137): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
E/SQLiteDatabase( 8137): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8137): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
E/SQLiteDatabase( 8137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8137): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8137): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8137): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8137): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8137): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8137): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/LNoti   ( 8137): [b] open fail. SQLException occured
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8154): MountEmulatedStorage()
E/Zygote  ( 8154): v2
I/libpersona( 8154): KNOX_SDCARD checking this for 10042
I/libpersona( 8154): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8154 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager(  897): Killing 6862:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
I/SELinux ( 8154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/EventHub(  897): Removing device '/dev/input/event4' due to inotify event
E/SELinux ( 8154): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8154): TimaSignature is unavailable
D/ActivityThread( 8154): Added TimaKeyStore provider
W/libprocessgroup(  897): failed to open /acct/uid_10058/pid_6862/cgroup.procs: No such file or directory
D/ResourcesManager( 8154): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
I/EventHub(  897): Removing device '/dev/input/event5' due to inotify event
W/ResourcesManager( 8154): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8154): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ContextImpl( 8154): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8154): Unable to setupGraphicsSupport due to missing cache directory
F/libc    ( 8154): Fatal signal 7 (SIGBUS), code 2, fault addr 0xafabe000 in tid 8154 (sdk.samsunglink)
F/libc    ( 8154): Failed while talking to debuggerd: Broken pipe
E/audit_log( 1996): File locking failed. error= Bad file number
E/audit_log( 1996): File locking failed. error= Bad file number
I/ActivityManager(  897): Process com.samsung.android.sdk.samsunglink (pid 8154)(adj 0) has died(82,599)
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8172): MountEmulatedStorage()
E/Zygote  ( 8172): v2
I/libpersona( 8172): KNOX_SDCARD checking this for 10045
I/libpersona( 8172): KNOX_SDCARD not a persona
I/Zygote  (  312): Process 8154 exited due to signal (7)
I/ActivityManager(  897): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=8172 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  312): Explicit concurrent mark sweep GC freed 8716(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 269us total 13.313ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.386ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.222ms
I/SELinux ( 8172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8172): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL

```
