#### Test 623445121bdd37c_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
D/TMNetworkReceiver( 9302): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive() Exit 
D/TMNetworkReceiver( 9302): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
I/iu.UploadsManager( 4482): End new media; added: 0, uploading: 0, time: 51 ms
D/TMSLogRemovalReceiver( 9302): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver( 9302): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 9302): TMLogRemovalReceiver.onReceive() Exit
--------- beginning of system
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3526): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager( 8023): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/ActivityManager( 3526): Killing 8481:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
I/splitIntent( 3526): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3526): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
D/AuthorizationBluetoothService( 4202): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 4202): [239] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4482): Restart initialization of location
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3526): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 3526): Waited long enough for: ServiceRecord{186e7077 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
W/GCoreFlp( 4202): No location to return for getLastLocation()
W/FusedLocationProvider( 4202): location=null
I/splitIntent( 3526): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
D/Widget  ( 8402): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
D/Widget  ( 8402): onReceive android.appwidget.action.APPWIDGET_UPDATE
D/Widget  ( 8402): widgetUpdate 5
D/RCPManagerService( 3526): exchangeData() failure , invalid userId
E/SQLiteLog( 8715): (284) automatic index on view_events(_id)
I/SettingSearch/SearchIntentReceiver( 7681): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 7681): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
I/SettingSearch/SearchIntentReceiver( 7681): InitTitleDBThread start --> mDoingInitTitleDB : true
I/SettingSearch/SearchIntentReceiver( 7681): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 7681): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
D/CalendarAlarmManager( 8715): sys current time:1457591131290
D/CalendarAlarmManager( 8715): reminder amount:0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9335): MountEmulatedStorage()
I/libpersona( 9335): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9335): v2
I/libpersona( 9335): KNOX_SDCARD not a persona
I/SELinux ( 9335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=9335 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SettingSearch/SettingsSearchManager( 7681): Infomation -> numtitleinfo : 0 numSearchinfo : 367
D/TimaKeyStoreProvider( 9335): TimaSignature is unavailable
D/ActivityThread( 9335): Added TimaKeyStore provider
E/MTPJNIInterface( 9284): Status for mount/Unmount :removed
E/MTPJNIInterface( 9284): SDcard is not available
D/ResourcesManager( 9335): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
E/        ( 9284): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
E/MTPJNIInterface( 9284): Status for mount/Unmount :removed
E/MTPJNIInterface( 9284): SDcard is not available
E/SQLiteLog( 9284): (21) API call with NULL database connection pointer
E/SQLiteLog( 9284): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog( 9284): (21) API call with NULL database connection pointer
E/SQLiteLog( 9284): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9284): (21) API call with NULL database connection pointer
E/SQLiteLog( 9284): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9284): (21) API call with NULL database connection pointer
E/SQLiteLog( 9284): (21) misuse at line 105958 of [9491ba7d73]
W/MTPRx   ( 9284): notification from stack 2
D/        ( 9284): [mtp_init_device] Library open with 32 bits.
D/        ( 9284): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 9284): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        ( 9284): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 9284):  [sua_support_present:1277] returning false 
D/        ( 9284): *****Starting mtp_io()
D/        ( 9284): [mtp_start_io] source_thread Creation 
W/MTPRx   ( 9284): notification from stack 3
D/        ( 9284): [mtp_start_io] sink_thread Creation 
D/        ( 9284): [mtp_start_io:368] sink thread created so set th_sink
I/SettingSearch/SettingsSearchManager( 7681):  Infomation -> getItem size : 367
I/DIAGMON_AGENT( 9335): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
D/ResourcesManager( 7681): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 7681): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
W/ResourcesManager( 7681): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7681): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7681): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7681): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 7681): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3526): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/DIAGMON_AGENT( 9335): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 9335): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 9335): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/ActivityManager( 3526): Killing 8273:com.sec.android.app.popupuireceiver/1000 (adj 13): bgCount ##31
I/DBG_DM  ( 5898): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
D/LocationWidgetUtils( 8678): getUpcommingInstances() start: 1457591131493, end: 1458169199999
D/LocationWidgetUtils( 8678): getUpcommingInstances() DB begin time >= start:1457591131493, DB begin time <= end:1458169199999
I/GAV2    ( 8801): Thread[GAThread,5,main]: No campaign data found.
D/LWLocationManager( 8678): getDeviceLocationId :  id = -100
D/LocationWidgetApplication( 8678): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9362): MountEmulatedStorage()
I/libpersona( 9362): KNOX_SDCARD checking this for 10035
E/Zygote  ( 9362): v2
I/libpersona( 9362): KNOX_SDCARD not a persona
I/SELinux ( 9362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9362 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 9362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3526): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/TimaKeyStoreProvider( 9362): TimaSignature is unavailable
D/ActivityThread( 9362): Added TimaKeyStore provider
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/SettingSearch/SearchIntentReceiver( 7681): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 7681): LOCALE_CHANGED call search setting db finish!!
I/FeatureConfig( 9362): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 9362): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 9362): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 9362): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/ActivityManager( 3526): Killing 8785:com.samsung.android.app.powersharing/u0a149 (adj 13): bgCount ##31
W/ResourcesManager( 9362): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/ResourcesManager( 9362): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  ( 9379): MountEmulatedStorage()
I/libpersona( 9379): KNOX_SDCARD checking this for 10050
E/Zygote  ( 9379): v2
I/libpersona( 9379): KNOX_SDCARD not a persona
I/SELinux ( 9379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/SELinux ( 9379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/SettingSearch/SearchIntentReceiver( 7681): InitTitleDBThread start --> mDoingInitTitleDB : true
E/SELinux ( 9379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 9362): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/ActivityManager( 3526): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=9379 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 9362): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/TimaKeyStoreProvider( 9379): TimaSignature is unavailable
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ActivityThread( 9379): Added TimaKeyStore provider
D/ResourcesManager( 9379): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 9379): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9379): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 9362): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager( 9362): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 9362): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/art     ( 3526): Explicit concurrent mark sweep GC freed 49447(3MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.693ms total 96.353ms
D/ResourcesManager( 9362): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/ResourcesManager( 9362): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 9362): system/finder_cp/cpdata.xml file not found
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3526): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PackageManager( 3526): findPreferredActivity: No PreferredActivities set
I/SettingSearch/SearchIntentReceiver( 7681): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 7681): LOCALE_CHANGED call search setting db finish!!
D/NearbySource( 9379): Nearby Source Create!
D/NearbyContext( 9379): Nearby Context Create!
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9379): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 9379): Samsung link source created
D/ContactProvider( 9379): getAllContactInfoList Start
D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/UpdateIcingCorporaServi( 4056): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager( 3526): Killing 8913:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9403): MountEmulatedStorage()
E/Zygote  ( 9403): v2
I/libpersona( 9403): KNOX_SDCARD checking this for 10079
I/libpersona( 9403): KNOX_SDCARD not a persona
I/SELinux ( 9403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=9403 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 9394): 
D/AndroidRuntime( 9394): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9394): CheckJNI is OFF
D/AndroidRuntime( 9394): readGMSProperty: start
D/AndroidRuntime( 9394): readGMSProperty: already setted!!
D/AndroidRuntime( 9394): readGMSProperty: end
D/AndroidRuntime( 9394): addProductProperty: start
D/ContactProvider( 9379): getAllContactInfoList End
I/syncContacts( 9379): thread: 1203, sync time = 66
D/TimaKeyStoreProvider( 9403): TimaSignature is unavailable
D/ActivityThread( 9403): Added TimaKeyStore provider
D/ResourcesManager( 9403): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
D/ResourcesManager( 4482): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/FileShare-Server( 9403): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
W/ProcessCpuTracker( 3526): Skipping unknown process pid 8913
E/Zygote  ( 9422): MountEmulatedStorage()
E/Zygote  ( 9422): v2
I/libpersona( 9422): KNOX_SDCARD checking this for 1000
I/libpersona( 9422): KNOX_SDCARD not a persona
I/SELinux ( 9422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9422): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=9422 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3526): Killing 4163:com.google.process.gapps/u0a14 (adj 13): bgCount ##31
D/TimaKeyStoreProvider( 9422): TimaSignature is unavailable
D/ActivityThread( 9422): Added TimaKeyStore provider
D/ResourcesManager( 9422): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager( 9422): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3526): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9441): MountEmulatedStorage()
I/libpersona( 9441): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9441): v2
I/libpersona( 9441): KNOX_SDCARD not a persona
E/AffinityControl( 9394): AffinityControl: registerfunction enter
I/SELinux ( 9441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=9441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3526): Killing 7938:com.android.vending/u0a31 (adj 13): bgCount ##31
E/SELinux ( 9441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 2882): Explicit concurrent mark sweep GC freed 8804(374KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 336us total 11.895ms
D/AndroidRuntime( 9394): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 9441): TimaSignature is unavailable
D/ActivityThread( 9441): Added TimaKeyStore provider
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 440us total 10.909ms
D/ResourcesManager( 9441): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
E/PersonaManagerService( 3526): inState():  stateMachine is null !!
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 551us total 10.287ms
I/PersonaManagerService( 3526): PersonaId don't exist
I/ActivityManager( 3526): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3526): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService( 3526): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3526  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3526): mDVFSHelper.acquire()
D/FocusedStackFrame( 3526): Set to : 0
E/libEGL  ( 4002): call to OpenGL ES API with no current context (logged once per thread)
D/Launcher.HomeView( 4002): onPause
D/Launcher( 4002): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 9394): Shutting down VM
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 3526): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3526): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3526): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3526): setHoveringSpenCustomIcon IconType is same.1
D/ShortcutReceiver( 9441):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
I/SurfaceFlinger( 2851): id=10 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 9458): MountEmulatedStorage()
E/Zygote  ( 9458): v2
I/libpersona( 9458): KNOX_SDCARD checking this for 10690
I/libpersona( 9458): KNOX_SDCARD not a persona
I/SELinux ( 9458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9458 uid=10690 gids={50690, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 9458): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PowerManagerService( 3526): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3526): [s] DisplayPowerCallbacks : onStateChanged()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 3526): lcd : 1 +
D/StatusBarManagerService( 3526): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 9458): TimaSignature is unavailable
D/ActivityThread( 9458): Added TimaKeyStore provider
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
I/MicrophoneInputStream( 4056): mic_close gfk@1d1e29
V/ActivityThread( 4002): updateVisibility : ActivityRecord{1eca8d1a token=android.os.BinderProxy@1856906e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/AudioPolicyManager( 2857): stopInput() input 16
V/AudioPolicyManager( 2857): releaseInput() 16
V/AudioPolicyManager( 2857): closeInput(16)
I/HotwordRecognitionRnr( 4056): Stopping hotword detection.
I/HotwordRecognitionRnr( 4056): Hotword detection finished
E/Zygote  ( 9473): MountEmulatedStorage()
I/libpersona( 9473): KNOX_SDCARD checking this for 10147
E/Zygote  ( 9473): v2
I/libpersona( 9473): KNOX_SDCARD not a persona
D/AudioHardwareTinyALSA( 2857): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2857): Close mHandle:afea9600
I/SELinux ( 9473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9473 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9473): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/lights  ( 3526): lcd : 1 -
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager( 3526): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/Launcher.HomeView( 4002): onStop
I/ActivityManager( 3526): Killing 8314:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
V/ActivityThread( 4002): updateVisibility : ActivityRecord{1eca8d1a token=android.os.BinderProxy@1856906e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/AudioHardwareTinyALSA( 2857): closeInputStream +
D/TinyUCM ( 2857): Disable Input dev(0x80000004)
D/TinyUCM ( 2857): set channel: None
D/AudioHardwareTinyALSA( 2857): Entering AudioStreamInALSA standby mode
V/AudioPolicyManager( 2857): releaseInput() exit
D/TimaKeyStoreProvider( 9473): TimaSignature is unavailable
D/ActivityThread( 9473): Added TimaKeyStore provider
D/StatusBarManagerService( 3526): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 9458): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/ResourcesManager( 9473): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/Launcher( 4002): onTrimMemory. Level: 20
W/ResourcesManager( 9473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/WebViewFactory( 9458): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 9458): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 9458): Loading: webviewchromium
I/LibraryLoader( 9458): Time to load native libraries: 3 ms (timestamps 9236-9239)
I/LibraryLoader( 9458): Expected native library version number "",actual native library version number ""
D/ResourcesManager( 4056): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
V/WebViewChromiumFactoryProvider( 9458): Binding Chromium to main looper Looper (main, tid 1) {23e63fa7}
I/LibraryLoader( 9458): Expected native library version number "",actual native library version number ""
I/chromium( 9458): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/UpdateIcingCorporaServi( 4056): UpdateCorporaTask done [took 376 ms] updated apps [took 375 ms] 
I/BrowserStartupController( 9458): Initializing chromium process, renderers=0
W/art     ( 9458): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 9458): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 9458): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 9458): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 9458): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 9458): 311962708: getState() :  mService = null. Returning STATE_OFF
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9527): MountEmulatedStorage()
I/libpersona( 9527): KNOX_SDCARD checking this for 10014
E/Zygote  ( 9527): v2
I/libpersona( 9527): KNOX_SDCARD not a persona
,I/SELinux ( 9527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=9527 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 9527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9527): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9527): TimaSignature is unavailable
,D/ActivityThread( 9527): Added TimaKeyStore provider
,W/chromium( 9458): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 9458): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/ResourcesManager( 9527): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GservicesProvider( 9527): Gservices pushing to system: true; secure/global: true
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/art     ( 9458): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 9458): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 9458): CordovaWebView is running on device made by: samsung
,W/art     ( 9458): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 9458): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 9458): performCreate Call secproduct feature valuefalse
D/Activity( 9458): performCreate Call debug elastic valuetrue
,I/GoogleHttpClient( 9527): GMS http client unavailable, use old client
,D/OpenGLRenderer( 9458): Render dirty regions requested: true
,D/ActivityManager( 3526): post active user change for 0
D/KnoxTimeoutHandler( 3526): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3526): handleActiveUserChange for user 0
,D/ResourcesManager( 9527): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/SurfaceFlinger( 2851): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/GoogleHttpClient( 9527): GMS http client unavailable, use old client
,D/PointerIcon( 3526): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3526): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3526): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3526): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 9458): Initialized EGL, version 1.4
I/OpenGLRenderer( 9458): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278897904 
,D/OpenGLRenderer( 9458): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 9458): Enabling debug mode 0
,D/mali_winsys( 9458): new_window_surface returns 0x3000,  [1440x2560]-format:1
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 4482): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/InputMethodManagerService( 3526): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/Zygote  ( 9566): MountEmulatedStorage()
E/Zygote  ( 9566): v2
I/libpersona( 9566): KNOX_SDCARD checking this for 10031
I/libpersona( 9566): KNOX_SDCARD not a persona
,I/SELinux ( 9566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 3526): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9566 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9566): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/PackageBroadcastService( 4482): Null package name or gms related package.  Ignoreing.
W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 3526): Displayed com.example.hello/.MainActivity: +438ms
I/Timeline( 9458): Timeline: Activity_idle id: android.os.BinderProxy@1a7e449a time:39530
I/Icing   ( 4482): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager( 3526): Killing 9052:com.sec.android.app.sns3/u0a37 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9566): TimaSignature is unavailable
,D/ActivityThread( 9566): Added TimaKeyStore provider
,D/ResourcesManager( 9566): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/chromium( 9458): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 9458): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 9458): Set native->JS mode to OnlineEventsBridgeMode
,I/SurfaceFlinger( 2851): id=8 Removed Mauncher (4/9)
,I/SurfaceFlinger( 2851): id=8 Removed Mauncher (-2/9)
,I/chromium( 9458): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 9458): 
,D/Finsky  ( 9566): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/jxcore_app_log( 9458): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360537856
D/JX-Cordova( 9458): jxcore cordova android initializing
,D/Finsky  ( 9566): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 9566): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9566): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/jxcore-log( 9458): Initializing JXcore engine
W/jxcore-log( 9458): JXcore engine is ready
,E/SQLiteLog( 9527): (283) recovered 516 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,W/jxcore-log( 9458): Starting JXcore engine
,I/SurfaceFlinger( 2851): id=10 Removed iello (7/8)
,I/SurfaceFlinger( 2851): id=10 Removed iello (-2/8)
,D/Finsky  ( 9566): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 9566): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 9566): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/System.out( 9566): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 9566): (HTTPLog)-Static: isShipBuild true
I/System.out( 9566): (HTTPLog)-Thread-1253-980716141: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 9566): (HTTPLog)-Static: isSBSettingEnabled false
,D/Ads     ( 9566): Skipping gmscore version check
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  ( 9566): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/auditd  ( 4542): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3526): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/BluetoothManager( 8892): getConnectedDevices
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8892): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8892): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8892): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SecurityLogAgent:SEDenialService( 3526): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/BluetoothManager( 8892): getConnectedDevices
,D/BluetoothManager( 8892): getConnectedDevices
,D/BluetoothManager( 8892): getConnectedDevices
,D/BluetoothManager( 8892): getConnectedDevices
,D/BluetoothManager( 8892): getConnectedDevices
,D/BluetoothManager( 8892): getConnectedDevices
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/BluetoothManager( 8892): getConnectedDevices
,D/BluetoothManager( 8892): getConnectedDevices
,E/Zygote  ( 9633): MountEmulatedStorage()
E/Zygote  ( 9633): v2
I/libpersona( 9633): KNOX_SDCARD checking this for 10135
I/libpersona( 9633): KNOX_SDCARD not a persona
,I/SELinux ( 9633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=9633 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 9633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9633): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 9084:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,W/jxcore-log( 9458): Platform android
W/jxcore-log( 9458): 
W/jxcore-log( 9458): Process ARCH arm
W/jxcore-log( 9458): 
,D/TimaKeyStoreProvider( 9633): TimaSignature is unavailable
,D/ActivityThread( 9633): Added TimaKeyStore provider
,D/ResourcesManager( 9633): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/jxcore-log( 9458): JXcore Cordova bridge is ready!
I/jxcore-log( 9458): 
,W/jxcore-log( 9458): JXcore engine is started
,D/CustomFrequencyManagerService( 3526): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3526  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3526): mDVFSHelper.release()
I/Timeline( 3526): Timeline: Activity_windows_visible id: ActivityRecord{36087241 u0 com.example.hello/.MainActivity t27} time:39907
D/CustomFrequencyManagerService( 3526): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3526  pkgName : ACTIVITY_RESUME_BOOSTER@6
,E/jxcore-log( 9458): >> samsung-SM-N910C
E/jxcore-log( 9458): 
,I/jxcore-log( 9458): Total memory 2970812416
I/jxcore-log( 9458): 
,I/jxcore-log( 9458): Free memory 83845120
I/jxcore-log( 9458): 
I/jxcore-log( 9458): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9458): 
I/jxcore-log( 9458): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9458): 
,I/jxcore-log( 9458): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9458): 
,I/jxcore-log( 9458): Size 1440 2560
I/jxcore-log( 9458): 
,I/jxcore-log( 9458): Screen Brightness 134
I/jxcore-log( 9458): 
,E/jxcore-log( 9458): Dummy Error Log.
E/jxcore-log( 9458): 
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MusicStore( 9633): Database version: 104
,D/ResourcesManager( 9633): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 9633): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9633): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9633): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9633): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9633): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c88418b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9633): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9633): GMSCore installation verified
,I/ConfigStore( 9633): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9633): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9633): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9633): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3526): getStreamVolume 3 index 0
,I/MediaRouter( 9633): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9663): MountEmulatedStorage()
E/Zygote  ( 9663): v2
I/libpersona( 9663): KNOX_SDCARD checking this for 10063
I/libpersona( 9663): KNOX_SDCARD not a persona
,I/SELinux ( 9663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9663): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9663 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicLeanback( 9633): Conditions not met for autocaching.
I/MusicLeanback( 9633): Stop autocaching.
,I/MusicLeanback( 9633): Stop autocaching.
,I/MusicLeanback( 9633): Stop autocaching.
,D/TimaKeyStoreProvider( 9663): TimaSignature is unavailable
,D/ActivityThread( 9663): Added TimaKeyStore provider
I/MusicLeanback( 9633): Stop autocaching.
I/MusicLeanback( 9633): Stop autocaching.
,D/ResourcesManager( 9663): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/CustomFrequencyManagerService( 3526): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3526  tag : ACTIVITY_RESUME_BOOSTER@6
,I/GHttpClientFactory( 9633): Using the GMSCore's GoogleHttpClient
,D/VRSetupWizardStub/PackageIntentReceiver( 9663): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver( 9663): ACTION_PACKAGE_ADDED
,I/HomeSyncInstallReceiver( 3969): This pkg do not need BT addr. Do nothing
,I/splitIntent( 3526): Split this intent : android.intent.action.PACKAGE_ADDED !!   mSplitNum[0]=15, mSplitNum[1]=27, mSplitNum[2]=39 divideNum= 12 r.nextReceiver= 3 receivers.size=51
,I/splitIntent( 3526): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/WearableClient( 9633): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 9633): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 9633): WearableClientImpl.onPostInitHandler: done
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/WearableClient( 9633): WearableClientImpl.onPostInitHandler: done
,E/Zygote  ( 9684): MountEmulatedStorage()
E/Zygote  ( 9684): v2
I/libpersona( 9684): KNOX_SDCARD checking this for 10101
I/libpersona( 9684): KNOX_SDCARD not a persona
,I/SELinux ( 9684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9684 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9684): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9684): TimaSignature is unavailable
,E/Zygote  ( 9698): MountEmulatedStorage()
I/libpersona( 9698): KNOX_SDCARD checking this for 10010
E/Zygote  ( 9698): v2
I/libpersona( 9698): KNOX_SDCARD not a persona
D/ActivityThread( 9684): Added TimaKeyStore provider
,I/SELinux ( 9698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.facebook.system for broadcast com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver: pid=9698 uid=10010 gids={50010, 9997} abi=armeabi-v7a
,E/SELinux ( 9698): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9698): TimaSignature is unavailable
,D/ActivityThread( 9698): Added TimaKeyStore provider
,D/ResourcesManager( 9684): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9698): creating new AssetManager and set to /data/app/com.facebook.system-1/base.apk
,E/Zygote  ( 9717): MountEmulatedStorage()
E/Zygote  ( 9717): v2
I/libpersona( 9717): KNOX_SDCARD checking this for 10019
I/libpersona( 9717): KNOX_SDCARD not a persona
,I/SELinux ( 9717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=9717 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/GmsUtils( 9633): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 9633): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/TimaKeyStoreProvider( 9717): TimaSignature is unavailable
,D/ActivityThread( 9717): Added TimaKeyStore provider
,E/ActivityThread( 9633): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@357a5727 that was originally bound here
E/ActivityThread( 9633): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@357a5727 that was originally bound here
E/ActivityThread( 9633): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 9633): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 9633): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread( 9633): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread( 9633): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 9633): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 9633): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 9633): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 9633): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 9633): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 9633): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 9633): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 9633): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 9633): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 9633): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 9633): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread( 9633): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread( 9633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread( 9633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 9633): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 9633): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread( 9633): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 9633): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 9633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 9633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/DocsApplication( 9684): Installing DEX configuration.
,D/DexInstaller( 9684): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 9684): Provided clientMode=RELEASE, packageInfo=PackageInfo{81f61bc com.google.android.apps.docs}
,D/ResourcesManager( 9717): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/TAG     ( 9684): onCreate()
,D/PackageBroadcastService( 4482): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/ActivityManager( 3526): Killing 9101:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 13): bgCount ##31
,D/CrossAppStateProvider( 9684): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/Mms/FreeMessageStatusReceiver( 8509): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 8509): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 8509): onHandleIntent: ACTION_PACKAGE_ADDED
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 9717): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 9717): onReceive called  PACKAGE_ADDED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9717): onReceive() : package name is not s health. Return !!!
,I/ActivityManager( 3526): Killing 9122:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 13): bgCount ##31
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4482): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4482): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9738): MountEmulatedStorage()
,E/Zygote  ( 9738): v2
I/libpersona( 9738): KNOX_SDCARD checking this for 10053
I/libpersona( 9738): KNOX_SDCARD not a persona
,I/SELinux ( 9738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/art     ( 4202): Explicit concurrent mark sweep GC freed 39855(2MB) AllocSpace objects, 21(336KB) LOS objects, 35% free, 29MB/45MB, paused 715us total 66.744ms
,I/SELinux ( 9738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=9738 uid=10053 gids={50053, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 9458): getBuffer is called!!!!
I/jxcore-log( 9458): 
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider( 9738): TimaSignature is unavailable
,D/ActivityThread( 9738): Added TimaKeyStore provider
,E/Zygote  ( 9755): MountEmulatedStorage()
E/Zygote  ( 9755): v2
I/libpersona( 9755): KNOX_SDCARD checking this for 1000
I/libpersona( 9755): KNOX_SDCARD not a persona
,I/SELinux ( 9755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 9145:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 332us total 18.570ms
,D/TimaKeyStoreProvider( 9755): TimaSignature is unavailable
,D/ActivityThread( 9755): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 320us total 9.563ms
,I/ActivityManager( 3526): Killing 9182:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 305us total 9.627ms
,W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3526): SIOP:: AP = 360, PST = 343, CUR = -702
,I/art     ( 3526): Explicit concurrent mark sweep GC freed 35876(2MB) AllocSpace objects, 17(4MB) LOS objects, 24% free, 48MB/64MB, paused 1.509ms total 114.993ms
,I/GAV3    ( 8892): Thread[GAThread,5,main]: No campaign data found.
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4482): Submit a task: k
,D/ResourcesManager( 9755): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/ResourcesManager( 9738): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/ResourcesManager( 9738): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9738): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9738): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4482): Processing package: com.example.hello
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/PCWCLIENTTRACE_LOG( 9755): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 9755): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 9755): new DMDBOpenHelper instance
,V/AlarmManager( 3526): waitForAlarm result :4
,I/Icing   ( 4482): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,D/GassUtils( 4482): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
D/k       ( 4482): Found info for package com.example.hello in db.
,D/Finsky  ( 9566): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/PCWCLIENTTRACE_PushUtil( 9755): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 9755): sales region : global
I/PCWCLIENTTRACE_PushUtil( 9755): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 9755): [onReceive] - android.intent.action.PACKAGE_ADDED
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9776): MountEmulatedStorage()
E/Zygote  ( 9776): v2
I/libpersona( 9776): KNOX_SDCARD checking this for 1000
I/libpersona( 9776): KNOX_SDCARD not a persona
,I/SELinux ( 9776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=9776 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 9776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Finsky  ( 9566): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/MyFiles ( 9738): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9793): MountEmulatedStorage()
E/Zygote  ( 9793): v2
I/libpersona( 9793): KNOX_SDCARD checking this for 10114
I/libpersona( 9793): KNOX_SDCARD not a persona
,I/SELinux ( 9793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.feed.platformads.AppInstallReceiver: pid=9793 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 9793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9793): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 9684): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/installd( 2861): system dir 0 : /system/app/
E/installd( 2861): system dir 1 : /system/priv-app/
E/installd( 2861): system dir 2 : /vendor/app/
E/installd( 2861): system dir 3 : /oem/app/
,D/TimaKeyStoreProvider( 9776): TimaSignature is unavailable
,D/ActivityThread( 9776): Added TimaKeyStore provider
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/TactileAssist( 3526): enable value -1
,I/TactileAssist( 3526): internal enable value -1
I/TactileAssist( 3526): intensity value -1
I/TactileAssist( 3526): saveAppList value true
I/TactileAssist( 3526): List of disabled apps :
,E/Zygote  ( 9810): MountEmulatedStorage()
E/Zygote  ( 9810): v2
I/libpersona( 9810): KNOX_SDCARD checking this for 10102
I/libpersona( 9810): KNOX_SDCARD not a persona
,I/SELinux ( 9810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 4482): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/ActivityManager( 3526): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=9810 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,D/Icing   ( 4482): Loaded CLD2 Version V2.0 - 20141016
,D/TimaKeyStoreProvider( 9793): TimaSignature is unavailable
,D/PackageManager( 3526): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/ActivityThread( 9793): Added TimaKeyStore provider
,I/Icing   ( 4482): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,D/ResourcesManager( 9776): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ResourcesManager( 9793): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9810): TimaSignature is unavailable
,D/ActivityThread( 9810): Added TimaKeyStore provider
,E/Zygote  ( 9830): MountEmulatedStorage()
E/Zygote  ( 9830): v2
I/libpersona( 9830): KNOX_SDCARD checking this for 10059
I/libpersona( 9830): KNOX_SDCARD not a persona
,I/SELinux ( 9830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9830 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 9830): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 9197:com.sec.modem.settings/1000 (adj 13): bgCount ##31
,D/ResourcesManager( 9810): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 9810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/System.out( 9566): Thread-1242(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/TimaKeyStoreProvider( 9830): TimaSignature is unavailable
,I/System.out( 9566): Thread-1242(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 9566): Thread-1242(ApacheHTTPLog):isShipBuild true
I/System.out( 9566): Thread-1242(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityThread( 9830): Added TimaKeyStore provider
,W/ResourcesManager( 9793): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,E/Zygote  ( 9851): MountEmulatedStorage()
E/Zygote  ( 9851): v2
I/libpersona( 9851): KNOX_SDCARD checking this for 10039
I/libpersona( 9851): KNOX_SDCARD not a persona
I/SELinux ( 9851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9851): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=9851 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 9230:com.sec.tcpdumpservice/1000 (adj 13): bgCount ##31
,I/System.out( 9566): Thread-1242 calls detatch()
,W/Finsky  ( 9566): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 9830): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 9830): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/[CarMode]( 9810): [DLApplication]-onCreate: Applicatino Started!
,I/System.out( 9566): Thread-1243 calls detatch()
,D/SampleAppCoreManager( 9810): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager( 9810): mContext is not null
,I/VlingoAndroidCore( 9810): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,D/TimaKeyStoreProvider( 9851): TimaSignature is unavailable
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ActivityThread( 9851): Added TimaKeyStore provider
,D/Compatibility( 9830): onReceive() it will make start service
,I/AppStateLoggerExceptionHandler( 9793): Installed uncaught exception handler for app state logging
,D/AppStateLogger( 9793): Attempting to open app state logging file
,D/AppStateLogger( 9793): Successfully opened app state logging file: /data/data/com.facebook.katana/app_state_logs/4bb7c908-6e17-b7da-f51b-c815e22a2c0f.txt
,D/ACRA    ( 9793): ACRA is enabled for com.facebook.katana, intializing...
,D/Compatibility( 9830): onHandleIntent()
,D/Compatibility( 9830): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10690, android.intent.extra.user_handle=0}]
D/ResourcesManager( 9851): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/Compatibility( 9830): found: 2
,D/Compatibility( 9830): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 9830): skipping ResolveInfo{188c1545 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 9830): considering ResolveInfo{1a7e449a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 9830): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 9830): enabling receiver ResolveInfo{29c651cb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,V/fb-UnpackingSoSource( 9793): locked dso store /data/data/com.facebook.katana/lib-main
,I/fb-UnpackingSoSource( 9793): dso store is up-to-date: /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource( 9793): releasing dso store lock for /data/data/com.facebook.katana/lib-main
,V/fb-UnpackingSoSource( 9793): locked dso store /data/data/com.facebook.katana/lib-assets
I/fb-UnpackingSoSource( 9793): dso store is up-to-date: /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource( 9793): releasing dso store lock for /data/data/com.facebook.katana/lib-assets
,V/fb-UnpackingSoSource( 9793): locked dso store /data/data/com.facebook.katana/lib-xzs
I/fb-UnpackingSoSource( 9793): dso store is up-to-date: /data/data/com.facebook.katana/lib-xzs
V/fb-UnpackingSoSource( 9793): releasing dso store lock for /data/data/com.facebook.katana/lib-xzs
,D/Compatibility( 9830): enabling receiver ResolveInfo{45edda8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/art     ( 9793): Thread[1,tid=9793,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
,V/appstatelogger( 9793): Registered App State Logger stream with Breakpad
,V/MemoryEnlargementHack( 9793): largeHeap already enabled in manifest
V/DexLibLoader( 9793): DLL.loadAll betaBuild:false flags:0x00000004
,D/Compatibility( 9830): enabling receiver ResolveInfo{1bddc0c1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/libpersona( 9873): KNOX_SDCARD checking this for 10014
E/Zygote  ( 9873): MountEmulatedStorage()
I/libpersona( 9873): KNOX_SDCARD not a persona
E/Zygote  ( 9873): v2
,I/SELinux ( 9873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=9873 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,V/dalvik-internals( 9793): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals( 9793): hooked signal using trap ()
V/dalvik-internals( 9793): hooked sysv_signal using trap ()
V/dalvik-internals( 9793): hooked bsd_signal using trap ()
V/dalvik-internals( 9793): hooked sigaction using jump ()
I/SELinux ( 9873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/dalvik-internals( 9793): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9793): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9793): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader( 9793): patched ART 5.0.x miranda bug
,E/SELinux ( 9873): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/Compatibility( 9830): enabling receiver ResolveInfo{46c1066 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,V/DexLibLoader( 9793): opening dex store /data/data/com.facebook.katana/dex
V/DexLibLoader( 9793): Secondary program dex metadata: [.root_relative]
V/DexLibLoader( 9793): Secondary program dex metadata: [.locators]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader( 9793): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Compatibility( 9830): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 4056): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,E/SPPClientService( 9851): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9851): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 9851): PushLog.txt file is not deleted.
D/SPPClientService( 9851): PushLog.txt file is not deleted.
D/SPPClientService( 9851): ============PushLog. stop!
,D/TimaKeyStoreProvider( 9873): TimaSignature is unavailable
,E/Zygote  ( 9891): MountEmulatedStorage()
I/libpersona( 9891): KNOX_SDCARD checking this for 10034
E/Zygote  ( 9891): v2
I/libpersona( 9891): KNOX_SDCARD not a persona
,I/SELinux ( 9891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ActivityThread( 9873): Added TimaKeyStore provider
I/SELinux ( 9891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=9891 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 9891): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Killing 9246:com.sec.android.app.sbrowser/u0a156 (adj 13): bgCount ##31
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,V/DexLibLoader( 9793): read status:9 check:faceb007faceb00e
V/DexLibLoader( 9793): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader( 9793): verified deps file
I/DexLibLoader( 9793): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader( 9793): installing MultiDexClassLoader before application classloader
D/TimaKeyStoreProvider( 9891): TimaSignature is unavailable
D/MultiDexClassLoader( 9793): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9793): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader( 9793): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9793): Setup multi dex took 0 ms.
V/DexLibLoader( 9793): optimization needed: no
,D/MemoryReductionHack( 9793): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
,D/ActivityThread( 9891): Added TimaKeyStore provider
E/Zygote  ( 9906): MountEmulatedStorage()
E/Zygote  ( 9906): v2
I/libpersona( 9906): KNOX_SDCARD checking this for 10042
I/libpersona( 9906): KNOX_SDCARD not a persona
I/SELinux ( 9906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3526): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=9906 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 9906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Killing 9266:com.sec.android.app.SecSetupWizard/1000 (adj 13): bgCount ##31
E/SELinux ( 9906): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 9873): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager( 9873): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9873): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ContextImpl( 8770): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
,W/GAV2    ( 9684): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/TimaKeyStoreProvider( 9906): TimaSignature is unavailable
,D/ActivityThread( 9906): Added TimaKeyStore provider
,I/GMPM    ( 9793): App measurement is starting up
,D/ResourcesManager( 9891): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/GMPM    ( 9793): getGoogleAppId failed with status: 10
E/GMPM    ( 9793): Uploading is not possible. App measurement disabled
,D/ResourcesManager( 4056): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/ActivityManager( 3526): Killing 9302:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##31
,D/ResourcesManager( 9906): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 9906): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
W/ResourcesManager( 9906): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 9566): Thread-1242 calls detatch()
,W/Finsky  ( 9566): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/System.out( 9891): Inside WakeupProvider
,W/StaticBindingVerifier( 9793): Verify
,E/DatabaseUtils( 9891): Writing exception to parcel
E/DatabaseUtils( 9891): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9891): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9891): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9891): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9891): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9891): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9891): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9891): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9891): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9891): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9891): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 9810): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 9810): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9810): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9810): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9810): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9810): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9810): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9810): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9810): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9810): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 9810): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 9810): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
I/UpdateIcingCorporaServi( 4056): UpdateCorporaTask done [took 164 ms] updated apps [took 164 ms] 
W/System.err( 9810): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 9810): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err( 9810): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err( 9810): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9810): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9810): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9810): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9810): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9810): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9810): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 9891): Writing exception to parcel
E/DatabaseUtils( 9891): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9891): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9891): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9891): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9891): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9891): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9891): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9891): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9891): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9891): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9891): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 9810): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 9810): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9810): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9810): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9810): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9810): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9810): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9810): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9810): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9810): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 9810): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 9810): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 9810): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err( 9810): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9810): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9810): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9810): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9810): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9810): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9810): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 9810): [DLApplication]-Init Called!:false
W/[CarMode]( 9810): [CommonUtil]-=========================================
W/[CarMode]( 9810): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode]( 9810): [CommonUtil]-=========================================
E/[CarMode]( 9810): [DLApplication]-Init Started!:true
I/VlingoApplication( 9891): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
I/[CarModeFW]( 9810): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 9810): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW]( 9810): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW]( 9810): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW]( 9810): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 9810): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW]( 9810): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW]( 9810): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW]( 9810): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 9810): ### android.os.Looper::loop(145)
I/[CarModeFW]( 9810): ### android.app.ActivityThread::main(5944)
I/[CarModeFW]( 9810): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 9810): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 9810): ### com.android.internal.os.ZygoteInit::main(1194)
D/BluetoothAdapter( 9891): 755982102: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9891): 755982102: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 9891): 755982102: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 9891): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
,I/MessageDataHandler( 9810): initialize
D/[CarModeFW]( 9810): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 9810): CDH-initiazlieCaches : after sync
I/MultiDex( 9873): VM with version 2.1.0 has multidex support
I/MultiDex( 9873): install
I/MultiDex( 9873): VM has multidex support, MultiDex support library is disabled.
D/BluetoothAdapter( 9810): 325479964: getState() :  mService = null. Returning STATE_OFF
W/LightSharedPreferencesImpl( 9793): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl( 9793): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9793): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl( 9793): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl( 9793): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl( 9793): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl( 9793): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl( 9793): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl( 9793): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl( 9793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl( 9793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl( 9793): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl( 9793): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl( 9793): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9793): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl( 9793): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl( 9793): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl( 9793): 	... 10 more
D/BluetoothAdapter( 9810): 325479964: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 9810): DrivingManager-initialize...
I/SL_DEBUG( 9906): isLoggable:: isProductShip = 1
I/SL_DEBUG( 9906): isLoggable:: SL_DEBUG_EXIST = false
I/SensorService( 3526): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3526): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3526): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3526): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3526): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
D/[CarModeFW]( 9810): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 9810): CDH-ContactDataHandler initiazlieCaches time : 33
D/[CarModeFW]( 9810): CDH-initiazlieCaches : end sync
,V/JNIHelp ( 9873): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/VlingoApplication( 9891): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/WifiService( 3526): New client listening to asynchronous messages
,D/VlingoApplication( 9891): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 9891): initQueue()
,W/ActivityThread( 9873): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9873): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@69ac950: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9873): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 9873): Reading stored module config
,D/ChimeraCfgMgr( 9873): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/fb4a(:<default>):UserScope( 9793): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9906): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,W/fb4a(:<default>):UserScope( 9793): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9906): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,I/MediaPlayer( 9810): Need to enable context aware info
V/MediaPlayer-JNI( 9810): native_setup
V/MediaPlayer( 9810): constructor
,W/fb4a(:<default>):UserScope( 9793): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,V/MediaPlayer( 9810): setListener
,V/Transcoder( 9906): Transcoder(0xb3c2f560)::constructor
V/Transcoder( 9906): addObitRecipient
,V/TMI-JNI ( 9906): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,V/xAnalytics( 9793): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics( 9793): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics( 9793): JNI_OnLoad XAnalyticsNative complete
,V/xAnalytics( 9793): tigon: 0x0 - xanalytics: 0xffffffff9331b280
,V/xAnalytics( 9793): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
D/[CarModeFW]( 9810): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
V/xAnalytics( 9793): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     ( 9793): Attempt to remove local handle scope entry from IRT, ignoring
,I/[CarModeFW]( 9810): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 9810): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457591134506
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457591134506
,D/CAR.SERVICE( 9873): Connecting to CarCallService...
,D/NativeLibraryUtils( 9873): Install completed successfully. count=14 extracted=0
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
I/art     ( 9873): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
I/art     ( 9873): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/CAR.SERVICE( 9873): com.google.android.projection.gearhead isn't installed.
D/[CarMode]( 9810): [DLServiceManager]-updateLocationList
,D/[CarMode]( 9810): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457591134522
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457591134523
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457591134524
D/[CarModeFW]( 9810): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457591134525
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457591134525
F/DLApplication( 9810): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
,I/[CarMode]( 9810): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW]( 9810): ContactDataHandler-getFavoriteContactList : cur len = 0
,E/Zygote  ( 9988): MountEmulatedStorage()
E/Zygote  ( 9988): v2
I/libpersona( 9988): KNOX_SDCARD checking this for 10045
I/libpersona( 9988): KNOX_SDCARD not a persona
,I/SELinux ( 9988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9988): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=9988 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/[CarMode]( 9810): [DLApplication]-Init End!:true
,D/[CarMode]( 9810): [TAG]-phone sound mode is: 0
V/[CarMode]( 9810): [DLApplication]-savePreviousGpsState
,D/CAR.TEL.Service( 9873): Creating a new CarCallService.
,D/[CarModeFW]( 9810): CalllogDataHandler-getCalllogList : cur len = 0
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 52
,V/[CarMode]( 9810): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/TP/SmsProvider( 3982): query,matched:2, calling pid = 9810
,D/[CarModeFW]( 9810): ContactDataHandler-getFavoriteContactList : cur len = 0
D/TP/SmsProvider( 3982): query,matched:2, calling pid = 9810
D/TP/SmsProvider( 3982): match 2:Elapsed time : 5.411 ms
,D/TP/SmsProvider( 3982): match 2:Elapsed time : 2.246 ms
D/[CarMode]( 9810): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode]( 9810): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/CAR.TEL.PhoneAdapter( 9873): Creating a new PhoneAdapter instance
,D/[CarModeFW]( 9810): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 57
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 57
,D/MessageDataHandler( 9810):  getInboxList smsCursor : 63
,W/ActivityManager( 3526): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,I/[CarMode]( 9810): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode]( 9810): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 87
,D/CAR.TEL.PhoneAdapter( 9873): setListener: com.google.android.gms.car.dn@22bc605f
D/TimaKeyStoreProvider( 9988): TimaSignature is unavailable
,I/UpdateManagerReceiver( 9810): Intent : android.intent.action.PACKAGE_ADDEDThu Mar 10 07:25:34 GMT+01:00 2016
,D/ActivityThread( 9988): Added TimaKeyStore provider
,D/DialogFlow( 9810): initQueue()
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/TP/MmsProvider( 3982): Query uri=content://mms/inbox, match=2, calling pid = 9810
,E/Zygote  (10007): MountEmulatedStorage()
I/libpersona(10007): KNOX_SDCARD checking this for 1000
E/Zygote  (10007): v2
I/libpersona(10007): KNOX_SDCARD not a persona
,I/SELinux (10007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=10007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 8402:com.samsung.android.snote/u0a160 (adj 15): bgCount ##31
,W/ActivityManager( 3526): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 9873): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 9873): Starting CarCallService with initial phone null
,D/[CarModeFW]( 9810): LocationDataHandler-No schedules found.
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10007): TimaSignature is unavailable
,D/ActivityThread(10007): Added TimaKeyStore provider
,D/ResourcesManager( 9988): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/Zygote  (10024): MountEmulatedStorage()
E/Zygote  (10024): v2
I/libpersona(10024): KNOX_SDCARD checking this for 10110
I/libpersona(10024): KNOX_SDCARD not a persona
,I/SELinux (10024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/System.out( 9891): INFO:Resource not found:/Common.properties Using default values
,I/SELinux (10024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10024): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=10024 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 8755:com.sec.providers.settingsearch/u0a181 (adj 13): bgCount ##31
,D/MessageDataHandler( 9810):  getInboxList mmsCursor : 96
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8760(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 336us total 10.899ms
,I/ActivityManager( 3526): Killing 8801:com.google.android.gm/u0a122 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(10024): TimaSignature is unavailable
,D/ActivityThread(10024): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 268us total 8.487ms
,D/CAR.SERVICE( 9873): Package validated; name: com.android.vending
,I/ActivityManager( 3526): Killing 9335:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 659us total 9.802ms
,D/TP/MmsProvider( 3982): Query uri=content://mms, match=0, calling pid = 9810
,D/ResourcesManager(10024): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,I/Icing   ( 4482): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,D/[CarModeFW]( 9810): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,D/ResourcesManager(10007): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/Icing   ( 4482): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/ContextImpl(10007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,I/SA      ( 9988): [SSP] onCreated
,E/Zygote  (10041): MountEmulatedStorage()
E/Zygote  (10041): v2
I/libpersona(10041): KNOX_SDCARD checking this for 10003
I/libpersona(10041): KNOX_SDCARD not a persona
,I/SELinux (10041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10041 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,I/SELinux (10041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/MessageDataHandler( 9810):  getInboxList mms,sms cursor join : 49
,E/SELinux (10041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/MessageDataHandler( 9810): getUnreadMessageCount :0
,D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 215
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3982): query,matched:0, calling pid = 9810
V/TP/MmsSmsProvider( 3982): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3982): match 0:Elapsed time : 1.852 ms
,D/TimaKeyStoreProvider(10041): TimaSignature is unavailable
,D/ActivityThread(10041): Added TimaKeyStore provider
,I/SA      ( 9988): [TPM] There is no property file
,D/ResourcesManager(10007): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/SA      ( 9988): [SCU] isHaveSA() - false
,I/SA      ( 9988): [TPM] getModelProperty : null
I/SA      ( 9988): [TPM] getCSCProperty : null
,E/FilterInstaller(10007): installFilters
,E/FilterInstaller(10007): There is no requred permission
,I/SA      ( 9988): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,E/Zygote  (10060): MountEmulatedStorage()
E/Zygote  (10060): v2
I/libpersona(10060): KNOX_SDCARD checking this for 10121
I/libpersona(10060): KNOX_SDCARD not a persona
,I/SELinux (10060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=10060 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux (10060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10060): TimaSignature is unavailable
,D/ActivityThread(10060): Added TimaKeyStore provider
,I/SA      ( 9988): [DM] init START
D/ResourcesManager(10041): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,I/ActivityManager( 3526): Killing 8700:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,D/TP/MmsSmsProvider( 3982): query,matched:13, calling pid = 9810
,D/TP/MmsSmsProvider( 3982): match 13:Elapsed time : 1.911 ms
,I/art     ( 3526): Explicit concurrent mark sweep GC freed 19829(1250KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 8.056ms total 90.115ms
,I/SA      ( 9988): [DM] This device is not a Vodafone
,D/UserAnalysis.PlaceProvider(10041): PlaceProvider onCreate()
,I/SA      ( 9988): checkReactivationActive for LOLLIPOP
I/SA      ( 9988): checkReactivationActive for reactiveActive
I/SA      ( 9988): setSupportRL : true
,D/ResourcesManager(10060): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/SA      ( 9988): [SCU] isHaveSA() - false
I/SA      ( 9988): support phone number id : false
I/SA      ( 9988): [DM] init END
I/SA      ( 9988): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      ( 9988): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10690 extra.user_handle.:0 ]
,D/MessageDataHandler( 9810):  getInboxList address cursor : 30
,D/TP/MmsSmsProvider( 3982): query,matched:0, calling pid = 9810
V/TP/MmsSmsProvider( 3982): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3982): match 0:Elapsed time : 1.252 ms
,I/ActivityManager( 3526): Killing 8843:com.google.android.talk/u0a125 (adj 15): bgCount ##31
,I/ActivityManager( 3526): Killing 8731:com.android.calendar/u0a164 (adj 15): bgCount ##32
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver(10060): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(10060): Not GearManger package! 
,E/Zygote  (10078): MountEmulatedStorage()
I/libpersona(10078): KNOX_SDCARD checking this for 10046
E/Zygote  (10078): v2
I/libpersona(10078): KNOX_SDCARD not a persona
D/UserAnalysis.SecureDbManager(10041): Key for secure DB is newly created
,I/SELinux (10078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/UserAnalysis.SecurePlaceDbHelper(10041): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10041): Create SecureDbHelper
,I/SELinux (10078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=10078 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/IntelligenceServiceApplication(10041): onCreate()
,D/TimaKeyStoreProvider(10078): TimaSignature is unavailable
,D/ActivityThread(10078): Added TimaKeyStore provider
,E/Zygote  (10093): MountEmulatedStorage()
E/Zygote  (10093): v2
I/libpersona(10093): KNOX_SDCARD checking this for 1000
I/libpersona(10093): KNOX_SDCARD not a persona
,I/SELinux (10093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=10093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MessageDataHandler( 9810):  getInboxList thread cursor : 51
,D/MessageDataHandler( 9810):  thread, addr result: 10
,I/[CarModeFW]( 9810): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 351
I/[CarModeFW]( 9810): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 1
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 354
,D/ResourcesManager(10078): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/ActivityManager( 3526): Killing 9403:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##31
,W/ResourcesManager(10078): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10078): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(10093): TimaSignature is unavailable
W/ResourcesManager(10078): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityThread(10093): Added TimaKeyStore provider
,V/Finsky  ( 9566): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ResourcesManager(10093): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,V/fb-UnpackingSoSource(10024): locked dso store /data/data/com.facebook.appmanager/lib-main
I/fb-UnpackingSoSource(10024): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(10024): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
,V/fb-UnpackingSoSource(10024): locked dso store /data/data/com.facebook.appmanager/lib-assets
I/fb-UnpackingSoSource(10024): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(10024): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(10024): locked dso store /data/data/com.facebook.appmanager/lib-xzs
,I/fb-UnpackingSoSource(10024): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource(10024): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ACRA    (10024): ACRA is enabled for com.facebook.appmanager, intializing...
,E/Minikin (10078): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/[CarModeFW]( 9810): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 9810): MyPlaceProvider-=============
D/[CarModeFW]( 9810): MyPlaceProvider-=============
D/[CarModeFW]( 9810): MyPlaceProvider-=============
D/[CarModeFW]( 9810): MyPlaceProvider-=============
D/[CarModeFW]( 9810): MyPlaceProvider-=============
D/[CarModeFW]( 9810): MyPlaceProvider-=============
D/[CarModeFW]( 9810): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 9810): MyPlaceProvider-==============
D/[CarModeFW]( 9810): MyPlaceProvider-==============
D/[CarModeFW]( 9810): MyPlaceProvider-==============
D/[CarModeFW]( 9810): MyPlaceProvider-==============
D/[CarModeFW]( 9810): MyPlaceProvider-==============
,V/DexLibLoader(10024): DLL.loadAll betaBuild:true flags:0x00000001
,V/dalvik-internals(10024): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(10024): hooked signal using trap ()
V/dalvik-internals(10024): hooked sysv_signal using trap ()
V/dalvik-internals(10024): hooked bsd_signal using trap ()
V/dalvik-internals(10024): hooked sigaction using jump ()
,V/DexLibLoader(10024): opening dex store /data/data/com.facebook.appmanager/dex
D/[CarModeFW]( 9810): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457591134924 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,V/DexLibLoader(10024): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
V/DexLibLoader(10024): read status:9 check:faceb007faceb00e
,V/DexLibLoader(10024): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader(10024): verified deps file
I/DexLibLoader(10024): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
E/[CarModeFW]( 9810): DestinationAvailableTableHandler-insert FAIL!
V/MultiDexClassLoader(10024): installing MultiDexClassLoader before application classloader
E/DestinationList( 9810): loadLocationDestinationList is null
D/[CarModeFW]( 9810): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 402
,D/MultiDexClassLoader(10024): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader(10024): Setup multi dex took 0 ms.
V/DexLibLoader(10024): optimization needed: no
,I/RelayReceiver_PinBoard(10078): onReceive... android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/RelayService_PinBoard(10078): RelayService Started!! : android.intent.action.PACKAGE_ADDED
,E/Zygote  (10112): MountEmulatedStorage()
I/libpersona(10112): KNOX_SDCARD checking this for 1000
E/Zygote  (10112): v2
I/libpersona(10112): KNOX_SDCARD not a persona
,I/SELinux (10112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 9422:com.sec.knox.bridge/1000 (adj 15): bgCount ##31
,I/GMPM    (10024): App measurement is starting up
,W/cn      (10024): Verify
,E/GMPM    (10024): getGoogleAppId failed with status: 10
,D/TimaKeyStoreProvider(10112): TimaSignature is unavailable
D/ActivityThread(10112): Added TimaKeyStore provider
E/GMPM    (10024): Uploading is not possible. App measurement disabled
,D/ResourcesManager(10112): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener(10112): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl(10112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl(10024): 	... 10 more
,E/Zygote  (10144): MountEmulatedStorage()
I/libpersona(10144): KNOX_SDCARD checking this for 10013
E/Zygote  (10144): v2
I/libpersona(10144): KNOX_SDCARD not a persona
,I/SELinux (10144): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10144): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10144): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=10144 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/appmanager(:<default>):b(10024): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/AcmsService(10112): Enter Oncreate
,D/AcmsServiceMonitor(10112): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10112): creating AcmsCore
D/AcmsCore(10112): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10112): AcmsCore
W/appmanager(:<default>):b(10024): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AcmsCore(10112): init
D/AcmsCore(10112): Looper handler is not null
D/AcmsCore(10112): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10112): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10112): Incrementing - Counter value: 1
D/AcmsCore(10112): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsCertificateMngr(10112): AcmsCertificateMngr
D/AcmsService(10112): onStartCommand
D/AcmsService(10112): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(10112): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10112): Incrementing - Counter value: 2
D/AcmsService(10112): Incremented Counter Value : onStartCommand
D/AcmsRevocationMngr(10112): AcmsRevocationMngr
,D/ActivityThread(10112): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/TimaKeyStoreProvider(10144): TimaSignature is unavailable
,D/ActivityThread(10144): Added TimaKeyStore provider
,D/ResourcesManager(10144): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/AcmsService(10112): Inside handle Intent
D/AcmsService(10112): App added - package name: com.example.hello
D/AcmsCore(10112): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10112): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10112): Incrementing - Counter value: 3
D/AcmsCore(10112): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10112): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10112): Decrementing - Counter value: 2
,W/appmanager(:<default>):QuickExperimentControllerImpl(10024): Exposure of experiment com.facebook.http.g.c@2790e509 occurred when no user was logged in
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/art     (10024): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
I/art     (10024): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,E/Zygote  (10176): MountEmulatedStorage()
I/libpersona(10176): KNOX_SDCARD checking this for 10160
E/Zygote  (10176): v2
I/libpersona(10176): KNOX_SDCARD not a persona
,I/ActivityManager( 3526): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=10176 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/System.out(10024): Thread-1346(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10024): Thread-1346(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10024): Thread-1346(ApacheHTTPLog):isShipBuild true
I/System.out(10024): Thread-1346(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10110
,I/System.out(10024): P[5]_NetworkDispatch1 calls detatch()
,W/appmanager(:<default>):ae(10024): Got java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname while executing fetchSessionlessGKInfo, retrying on a safe network stack
,I/System.out(10024): P[5]_NetworkDispatch1 calls detatch()
,E/appmanager(:<default>):p(10024): Sessionless gatekeeper fetch with SingleMethodRunner failed
E/appmanager(:<default>):p(10024): java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname
E/appmanager(:<default>):p(10024): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:427)
E/appmanager(:<default>):p(10024): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
E/appmanager(:<default>):p(10024): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1288)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:700)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:691)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:514)
E/appmanager(:<default>):p(10024): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:492)
E/appmanager(:<default>):p(10024): 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:302)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:477)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ae.c(FbHttpRequestProcessor.java:398)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ae.b(FbHttpRequestProcessor.java:342)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:328)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:256)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:1183)
E/appmanager(:<default>):p(10024): 	at com.facebook.http.common.ai.run(FbHttpRequestProcessor.java:1204)
E/appmanager(:<default>):p(10024): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p(10024): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
E/appmanager(:<default>):p(10024): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p(10024): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/appmanager(:<default>):p(10024): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
E/appmanager(:<default>):p(10024): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/appmanager(:<default>):p(10024): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/appmanager(:<default>):p(10024): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
E/appmanager(:<default>):p(10024): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager( 3526): Killing 9441:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/9441/oom_score_adj; errno=22
,I/ActivityManager( 3526): Killing 8678:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,I/SELinux (10176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AppStateLogger( 9793): Successfully dumped app state to log file
,D/TimaKeyStoreProvider(10176): TimaSignature is unavailable
,D/ActivityThread(10176): Added TimaKeyStore provider
,D/ResourcesManager(10176): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(10176): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10176): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10176): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Common  (10176): getScreenSize 1440 2560
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/JAM     (10176): Load The ApaService JNI
E/Zygote  (10206): MountEmulatedStorage()
I/libpersona(10206): KNOX_SDCARD checking this for 10160
E/Zygote  (10206): v2
I/libpersona(10206): KNOX_SDCARD not a persona
I/JAM     (10176): version: ProfessionalAudio_v1.0.b5
I/JAM     (10176): Try v1.0.b3 ...
,I/SELinux (10206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/Spen    (10176): SpenSdk version level = 55
D/Spen    (10176): SpenSdk jar version = 3.0.243
,D/Spen    (10176): SpenSdk apk version = 3.0.235
D/Spen    (10176): Server UPDATE Check
,I/SELinux (10206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/linker  (10176): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,E/SELinux (10206): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SPenError(10176): JNI_OnLoad
D/JNI_Bitmap(10176): Init .. Done
I/ActivityManager( 3526): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=10206 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/SPenSpiDecoder(10176): JNI_OnLoad .. Done
D/SPenError(10176): JNI_OnLoad Success
,D/PluginManager(10176): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager(10176): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(10176): JNI_OnLoad
D/Init_SPenSdk_Jni(10176): AndroidSDK: 21
D/Init_SPenSdk_Jni(10176): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(10176): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(10176): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(10176): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(10176): JNI_OnLoad .. Done
,D/Model_ObjectContainer_Jni(10176): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(10176): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(10176): check build type eng[0]
,D/Model_NoteDoc_Jni(10176): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(10176): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(10176): JNI_OnLoad .. Done
D/Model   (10176): OnLoad class Done
,D/spe_log (10176): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(10176): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(10176): Canvas JNI_OnLoad enter!!
,D/TimaKeyStoreProvider(10206): TimaSignature is unavailable
D/SPen_Library(10176): Canvas JNI_OnLoad Success
D/SPen_Library(10176): TextView JNI_OnLoad enter!!
,D/ActivityThread(10206): Added TimaKeyStore provider
D/SPen_Library(10176): TextView JNI_OnLoad Success
D/SPen_Library(10176): Text JNI_OnLoad enter!!
D/SPen_Library(10176): Text JNI_OnLoad Success
D/SPen_Library(10176): FontManager JNI_OnLoad enter!!
D/SPen_Library(10176): FontManager JNI_OnLoad Success
D/SPen_Library(10176): CapturePage JNI_OnLoad enter!!
D/SPen_Library(10176): CapturePage JNI_OnLoad Success
D/SPen_Library(10176): Multi JNI_OnLoad enter!!
,I/System.out( 9566): Thread-1243 calls detatch()
D/SPen_Library(10176): Multi JNI_OnLoad Success
D/SPen_Library(10176): Draw Engine JNI_OnLoad Success
,D/SPen_Library(10176): Brush JNI_OnLoad enter!!
,D/SPen_Library(10176): Brush JNI_OnLoad Success
W/Finsky  ( 9566): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/SPen_Library(10176): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(10176): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(10176): InkPen JNI_OnLoad enter!!
D/SPen_Library(10176): InkPen JNI_OnLoad Success
,D/Finsky  ( 9566): [1] DailyHygiene.access$600: Logging device features
,D/SPen_Library(10176): Marker JNI_OnLoad enter!!
D/SPen_Library(10176): Marker JNI_OnLoad Success
,D/SPen_Library(10176): Pencil JNI_OnLoad enter!!
,D/SPen_Library(10176): Pencil JNI_OnLoad Success
,D/SPen_Library(10176): NativePen JNI_OnLoad enter!!
D/SPen_Library(10176): NativePen JNI_OnLoad Success
V/AlarmManager( 3526): waitForAlarm result :4
,D/SPen_Library(10176): MontblancFountainPen JNI_OnLoad enter!!
D/ResourcesManager(10206): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/SPen_Library(10176): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(10176): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/Finsky  ( 9566): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
D/SPen_Library(10176): MontblancCalligraphyPen JNI_OnLoad Success
,W/ResourcesManager(10206): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10206): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10206): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/SPen_Library(10176): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(10176): MagicPen JNI_OnLoad Success
,D/SPen_Library(10176): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(10176): ObliquePen JNI_OnLoad Success
,D/SPen_Library(10176): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(10176): FountainPen JNI_OnLoad Success
D/Spen    (10176): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(10176): SPenSdk_init2
D/Init_SPenSdk(10176): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(10176): Total S Pen SDK Directory Size = 0
D/Spen    (10176): initialize complete
,W/linker  (10176): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/ResourcesManager(10176): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/DeviceConnectionService( 4202): client connected with version: 8296000
,E/Zygote  (10223): MountEmulatedStorage()
I/libpersona(10223): KNOX_SDCARD checking this for 10183
E/Zygote  (10223): v2
I/libpersona(10223): KNOX_SDCARD not a persona
,I/SELinux (10223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=10223 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/SELinux (10223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10223): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 9663:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
I/ActivityManager( 3526): Killing 9633:com.google.android.music:main/u0a135 (adj 15): bgCount ##32
,I/Icing   ( 4482): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,D/SNoteProvider(10206): onCreate enableSnoteSync = true
,D/Finsky  ( 9566): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 9566): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/TimaKeyStoreProvider(10223): TimaSignature is unavailable
,D/ActivityThread(10223): Added TimaKeyStore provider
,I/ActivityManager( 3526): Killing 9698:com.facebook.system/u0a10 (adj 13): bgCount ##31
,I/ActivityManager( 3526): Killing 9212:com.google.android.partnersetup/u0a17 (adj 15): bgCount ##32
,D/SNoteProvider(10206): ===query=== 
,V/Common  (10206): getScreenSize 1440 2560
,D/ResourcesManager(10223): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog(10223): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 4482): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,E/Zygote  (10245): MountEmulatedStorage()
E/Zygote  (10245): v2
I/libpersona(10245): KNOX_SDCARD checking this for 10190
I/libpersona(10245): KNOX_SDCARD not a persona
,I/SELinux (10245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10245 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (10245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 9379:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SNoteProvider(10206): ===query=== 
,D/TimaKeyStoreProvider(10245): TimaSignature is unavailable
,D/ActivityThread(10245): Added TimaKeyStore provider
,D/ResourcesManager(10245): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10245): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10245): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(10245): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10245): Widget is not attached.
,I/splitIntent( 3526): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3526): Killing 9717:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10024): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10024): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Zygote  (10263): MountEmulatedStorage()
E/Zygote  (10263): v2
I/libpersona(10263): KNOX_SDCARD checking this for 10135
I/libpersona(10263): KNOX_SDCARD not a persona
,I/SELinux (10263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=10263 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10263): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Waited long enough for: ServiceRecord{b6f72ca u0 com.sec.android.service.sm/.service.SecurityManagerService}
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8766(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 600us total 11.718ms
,D/TimaKeyStoreProvider(10263): TimaSignature is unavailable
,D/ActivityThread(10263): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 306us total 9.310ms
,D/ResourcesManager(10263): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(10024): Exposure of experiment com.facebook.imagepipeline.m.d@13513d3d occurred when no user was logged in
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 524us total 9.863ms
,W/appmanager(:<default>):aa(10024): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,W/appmanager(:<default>):aa(10024): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,I/art     (10024): Explicit concurrent mark sweep GC freed 52608(2MB) AllocSpace objects, 5(80KB) LOS objects, 22% free, 27MB/35MB, paused 640us total 26.591ms
,W/appmanager(:<default>):m(10024): No feature status reporters found; is this dead code?
,I/MusicStore(10263): Database version: 104
,D/ResourcesManager(10263): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(10263): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10263): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10263): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityThread(10263): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10263): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c88418b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10263): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10263): GMSCore installation verified
,I/ConfigStore(10263): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(10263): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10263): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10263): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3526): getStreamVolume 3 index 0
,I/MediaRouter(10263): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/CscFactoryReceiver( 3982): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 3982): Media DB Scanner finished.
D/CscFactoryReceiver( 3982): start service to Set Ringtone
,D/CscFactoryReceiver( 3982): start service to Set Notification
,D/CscFactoryReceiver( 3982): start service to Set Alarmtone
,D/CscUpdateService( 3982): onStart
,E/CscUpdateService( 3982): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3982): only ringtone update
D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 3982): onStart
E/CscUpdateService( 3982): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3982): only notification update
,E/CscParser( 3982): update(): xml file exist
D/CscUpdateService( 3982): onStart
E/CscUpdateService( 3982): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3982): only alarmtone update
,E/CscParser( 3982): update(): xml file exist
,E/CscParser( 3982): update(): xml file exist
,W/CSCSettings( 3982): Setting Ringtones (type) : 2
D/CscParser( 3982): MessageTone: null
W/CSCSettings( 3982): 1. Tag_Str: null
,W/CSCSettings( 3982): Setting Ringtones (type) : 4
D/CscParser( 3982): AlarmTone: null
W/CSCSettings( 3982): 1. Tag_Str: null
,W/CSCSettings( 3982): Setting Ringtones (type) : 1
,D/CscParser( 3982): RingTone: null
W/CSCSettings( 3982): 1. Tag_Str: null
,E/Zygote  (10299): MountEmulatedStorage()
I/libpersona(10299): KNOX_SDCARD checking this for 10004
E/Zygote  (10299): v2
I/libpersona(10299): KNOX_SDCARD not a persona
,I/SELinux (10299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=10299 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 8509:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10299): TimaSignature is unavailable
,D/ActivityThread(10299): Added TimaKeyStore provider
,D/ResourcesManager(10299): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,D/CountryDetector( 3526): No listener is left
,I/DCMProvider(10299): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@81f61bc Provider Ref Count:1
,I/DCMConfig(10299): [#DCM#] initializeTransport.SystemBroadcastReceiver  1 ms
,I/StorageController(10299): [#DCM#]  state through storage volume =  mounted
,I/StorageController(10299): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10299): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(10299): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager(10299): [#DCM#] setCriticalStateFromSystem screenOn =  true high siop = false camera running = false
,I/DCMPolicyManager(10299): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig(10299): [#DCM#] initializeTransport.DCMPolicyManager  11 ms
,I/DCMConfig(10299): [#DCM#] initializeTransport.MediaManager  12 ms
,I/DCMConfig(10299): [#DCM#] initializeTransport.DCMNRTManager  16 ms
,I/DCMConfig(10299): [#DCM#] No of CPU Core 8
I/DCMConfig(10299): [#DCM#] initializeTransport took  16 ms
I/DCMProvider(10299): [#DCM#] onCreate end 
,I/DCMNRTManager(10299): [#DCM#] intialize 
,I/SystemBroadcastReceiver(10299): [#DCM#] [DCM_Performance] onReceive completed in time  10 microsec. 
,I/SystemBroadcastReceiver(10299): [#DCM#] Calling notifyListeners. 
,I/StorageController(10299): [#DCM#]  state through storage volume =  mounted
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/StorageController(10299): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10299): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(10299): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
,I/StorageController(10299): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10299): [#DCM#]  state through storage volume =  removed
I/StorageController(10299): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController(10299): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController(10299): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/DCMUtilities(10299): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,I/WriterFactory(10299): [#DCM#] verifyLuceneDB ++ 
,I/SystemUtils(10299): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
,I/SystemUtils(10299): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities(10299): [#DCM#] OSUpgrade not required 
I/SystemBroadcastReceiver(10299): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10299): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  (10320): MountEmulatedStorage()
E/Zygote  (10320): v2
I/libpersona(10320): KNOX_SDCARD checking this for 10007
I/libpersona(10320): KNOX_SDCARD not a persona
,I/SELinux (10320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=10320 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Killing 9738:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,E/SELinux (10320): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WriterFactory(10299): [#DCM#] verifyLuceneDB OK breaking 
I/WriterFactory(10299): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory(10299): [#DCM#] TAXO in mode CREATE_OR_APPEND
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WriterFactory(10299): [#DCM#] Before facet 
I/WriterFactory(10299): [#DCM#] After facet=!null ? true
,D/TimaKeyStoreProvider(10320): TimaSignature is unavailable
,D/ActivityThread(10320): Added TimaKeyStore provider
,I/DCMUtilities(10299): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController(10299): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
I/DCMConfig(10299): [#DCM#] setSuccessState =  true
,D/ResourcesManager(10320): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,E/Watchdog( 3526): !@Sync 1
,I/ThumbnailProvider(10320): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver(10320): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService(10320): [START] processBroadcastIntent ...
,I/BroadcastProcessorService(10320): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10339): MountEmulatedStorage()
I/libpersona(10339): KNOX_SDCARD checking this for 10044
E/Zygote  (10339): v2
I/libpersona(10339): KNOX_SDCARD not a persona
,I/SELinux (10339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SettingsProvider( 3526): name = audio_safe_volume_state
,E/SELinux (10339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=10339 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/SystemInfo(10320): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService(10320): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService(10320): [START] DocumentService startDocumentService
,I/DocumentService(10320): DocumentService onCreate ... service
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10320): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10320): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/TimaKeyStoreProvider(10339): TimaSignature is unavailable
,D/ActivityThread(10339): Added TimaKeyStore provider
,D/ResourcesManager(10339): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(10339): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10339): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager(10339): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10339): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10339): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/SystemInfo(10320): [SIOP LEVEL] : -2
,I/DocumentServiceUtils(10320):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo(10320): DocumentService [SIOP LEVEL] changed to -2
E/SystemInfo(10320): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,I/DocumentService(10320): [BEGIN SYNC] DocumentService beginIndexing :17
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10320): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10359): MountEmulatedStorage()
E/Zygote  (10359): v2
I/libpersona(10359): KNOX_SDCARD checking this for 10050
I/libpersona(10359): KNOX_SDCARD not a persona
,I/SELinux (10359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=10359 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 9755:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,I/SystemInfo(10320): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10320): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10320): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/TimaKeyStoreProvider(10359): TimaSignature is unavailable
,D/ActivityThread(10359): Added TimaKeyStore provider
,D/ResourcesManager(10359): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(10359): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10359): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10359): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10359): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(10359): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10359): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10359): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SystemInfo(10320): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService(10320): [VERIFY] verifyThumbnailImages
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10320): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/DocumentService(10320): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService(10320): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :62
E/DocumentService(10320): [THUMBNAIL] Total Time taken for each file :0
E/        (10320): [INDEX] Total time taken for each file :0
,I/DocumentService(10320): DocumentService onDestroy start
,I/DocumentService(10320): DocumentService onDestroy end
,I/DocumentService(10320): DocumentService cleanupEverything start
,I/IndexParserThreadsManager(10320): InterruptedException: null
,I/ActivityManager( 3526): Killing 9362:com.samsung.android.app.galaxyfinder/u0a35 (adj 13): bgCount ##31
,I/SystemInfo(10320): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10320): DocumentService cleanupEverything end
I/Process (10320): Sending signal. PID: 10320 SIG: 9
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3526): Process com.samsung.indexservice (pid 10320)(adj 9) has died(91,1225)
,D/PackageManager( 3526): findPreferredActivity: No PreferredActivities set
,D/NearbySource(10359): Nearby Source Create!
D/NearbyContext(10359): Nearby Context Create!
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10359): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(10359): Samsung link source created
,D/ContactProvider(10359): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady(10359): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady(10359): handleMeidaScanFinish()
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10359): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10359): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10359): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10359): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/FaceInterface(10359): requestFaceScan() is called.
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
W/LocalSuggestAlbumData(10359): query fail: 
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/LocalSuggestAlbumData(10359): query fail: 
,I/FaceInterface(10359): startFaceScan() : waiting 5 sec
,E/Zygote  (10384): MountEmulatedStorage()
I/libpersona(10384): KNOX_SDCARD checking this for 10122
E/Zygote  (10384): v2
I/libpersona(10384): KNOX_SDCARD not a persona
,I/SELinux (10384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10384): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=10384 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10384): TimaSignature is unavailable
,D/ActivityThread(10384): Added TimaKeyStore provider
,D/ResourcesManager(10384): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 3721): Explicit concurrent mark sweep GC freed 5144(368KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 572us total 13.082ms
,I/art     ( 3526): Explicit concurrent mark sweep GC freed 22701(1444KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 1.576ms total 85.512ms
,D/ContactProvider(10359): getAllContactInfoList End
I/syncContacts(10359): thread: 1403, sync time = 111
W/ActivityManager( 3526): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread(10384): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3526): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MediaStoreImporter(10263): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,W/ActivityManager( 3526): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   (10384): getAccountsCursor
,W/ActivityManager( 3526): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 3526): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (10384): Observing account changes for notifications
,W/ActivityManager( 3526): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/GAV2    (10384): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 3526): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10422): MountEmulatedStorage()
E/Zygote  (10422): v2
I/libpersona(10422): KNOX_SDCARD checking this for 10022
I/libpersona(10422): KNOX_SDCARD not a persona
,I/SELinux (10422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10422): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=10422 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/Gmail   (10384): getAccountsCursor
E/Gmail   (10384): Error finding the version of the Email provider.....
E/Gmail   (10384): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (10384): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (10384): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (10384): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (10384): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (10384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (10384): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (10384): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(10384): We do not support migrating this version of the Email provider.
,I/ActivityManager( 3526): Killing 8892:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(10422): TimaSignature is unavailable
,D/ActivityThread(10422): Added TimaKeyStore provider
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(10422): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10422): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10422): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SQLiteLog(10384): (283) recovered 81 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/ResourcesManager( 4482): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/LocationWidgetApplication(10422): onCreate() : start
,D/LocationWidgetApplication(10422): countryCode = POLAND
,I/Gmail   (10384): notifyAccountChanged
,I/Gmail   (10384): getAccountsCursor
,I/Gmail   (10384): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/LocationManagerService( 3526): getProviders()=[]
,D/LocationManagerService( 3526): getProviders()=[passive]
D/LocationManagerService( 3526): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,I/Gmail   (10384): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (10384): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (10384): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/LWLocationManager(10422): mPrivacy is null
,W/ContextImpl(10422): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10446): MountEmulatedStorage()
I/libpersona(10446): KNOX_SDCARD checking this for 10173
E/Zygote  (10446): v2
I/libpersona(10446): KNOX_SDCARD not a persona
,I/SELinux (10446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10446 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 9684:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/ContextFramework:PrivacyManager(10422): Service for PrivacyManager is connected
,D/LWLocationManager(10422): Privacy service : STATUS_PLACE
D/LWLocationManager(10422): updateLocationStatus()
,D/TimaKeyStoreProvider(10446): TimaSignature is unavailable
,D/ActivityThread(10446): Added TimaKeyStore provider
,I/LocationWidgetFuctionData(10422): readDB
,I/LocationWidgetFuctionData(10422): selectedAppSize: 3
I/LocationWidgetFuctionData(10422): configPlaceList aroundMeItems
,D/ResourcesManager(10446): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,I/LocationWidgetFuctionData(10422): selectedAppSize: 3
,I/LocationWidgetFuctionData(10422): selectedAppSize: 3
,I/LocationWidgetFuctionData(10422): selectedAppSize: 3
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/LocationWidgetFuctionData(10422): selectedAppSize: 3
,V/TaskCloserActivity(10446): TaskCloserActivity enter()
,V/TaskCloserActivity(10446): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager( 3526): Killing 9776:com.policydm/1000 (adj 13): bgCount ##31
,I/splitIntent( 3526): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3526): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,I/art     ( 9527): Explicit concurrent mark sweep GC freed 9628(459KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 397us total 15.087ms
,D/AuthorizationBluetoothService( 4202): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4482): Restart initialization of location
I/Gmail   (10384): getAccountsCursor
,E/MDM     ( 4202): [251] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LWLocationManager(10422): findLocationType() : cursor_location.moveToFirst() return false!!
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 4202): No location to return for getLastLocation()
,W/FusedLocationProvider( 4202): location=null
,D/LWLocationManager(10422): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(10422): setShouldUpdateLocationId
D/LWLocationManager(10422): setShouldUpdateLocationId return false
D/LWLocationManager(10422): setShouldUpdateLocationId
D/LWLocationManager(10422): setShouldUpdateLocationId return false
D/LWLocationManager(10422): setShouldUpdateLocationId
D/LWLocationManager(10422): setShouldUpdateLocationId return false
D/LWLocationManager(10422): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/BatteryService( 3526): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3526): level:100, scale:100, status:2, health:2, present:true, voltage: 4222, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3526): online:4, current avg:-811, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1263
D/BatteryService( 3526): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3526): Plugged
I/MotionRecognitionService( 3526): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3698): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3698): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3698):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3698): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/splitIntent( 3526): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/BatteryMeterView( 3698): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3698): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BootupListener( 3982): ACTION_DRIVELINK
,D/SettingsProvider( 3526): name = drivelink_navigation
D/SettingsProvider( 3526): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3526): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3526): selectionArgs: false
D/SettingsProvider( 3526): selectionArgs: 1001
D/SecContentProvider( 3526): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3526): ret = -1
D/BootupListener( 3982): NAVI : com.here.app.maps
,D/SettingsProvider( 3526): name = internet_call_settings_visibility
D/SettingsProvider( 3526): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3526): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3526): selectionArgs: false
D/SettingsProvider( 3526): selectionArgs: 1001
D/SecContentProvider( 3526): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3526): ret = -1
D/BootupListener( 3982): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/Widget  (10176): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Finsky  ( 9566): [1266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Widget  (10176): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  (10176): widgetUpdate 5
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,V/GLSActivity( 4202): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 9566): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3526): Waited long enough for: ServiceRecord{24580490 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    ( 9473): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3526): Killing 7681:com.android.settings/1000 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BluetoothAdapter( 9458): disable()
,E/BluetoothManagerService( 3526): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 9458): packageName : com.example.hello
,D/WifiService( 3526): New client listening to asynchronous messages
D/SecContentProvider( 3526): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3526): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3526): mCursor = null
,D/WifiService( 3526): setWifiEnabled: false pid=9458, uid=10690
E/WifiService( 3526): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3526): name = wifi_on
I/jxcore-log( 9458): ****TEST TOOK:  5025  ms ****
I/jxcore-log( 9458): 
,I/jxcore-log( 9458): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9458): 
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3526): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3526): !@[ps] Screen__Off - 0 : timeout (0x4) (2)
I/PowerManagerService( 3526): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 3526): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3526): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3526): [s] DisplayPowerCallbacks : onStateChanged()
,D/InputManager-JNI( 3526): setDeviceInteractive: 0
D/PowerManagerService( 3526): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3526): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI( 3526): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/InputManager-JNI( 3526): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/InputManager-JNI( 3526): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI( 3526): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI( 3526): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3526): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService( 3526): handleSandman : startDream()
E/PowerManagerService( 3526): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 3526): Sleeping (uid 1000)...
D/PowerManagerService( 3526): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3526): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService( 3526): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger( 2851): id=12 createSurf (1440x2560),2 flag=404, DolorFade
,D/SContextService( 3526): 	.unregisterCallback : 1, client=
D/SContextService( 3526): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3c640926, Service = Auto Rotation, used = 1
,W/CAE     ( 3526): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3526): stop(ContextProvider.java:149)
V/CAE     ( 3526): clear(AutoRotationRunner.java:182)
V/CAE     ( 3526): disable(AutoRotationRunner.java:171)
I/CAE     ( 3526): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3526): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2869): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3526): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     ( 3526): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3526): Excessive delay in ColorFade : createEglContext: 11ms
,D/mali_winsys( 3526): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PermissionCache( 2851): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
,D/PowerManagerService( 3526): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 29ms
,D/AndroidRuntime(10487): 
D/AndroidRuntime(10487): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10487): CheckJNI is OFF
,D/AndroidRuntime(10487): readGMSProperty: start
D/AndroidRuntime(10487): readGMSProperty: already setted!!
,D/AndroidRuntime(10487): readGMSProperty: end
D/AndroidRuntime(10487): addProductProperty: start
,D/CAE     ( 3526): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     ( 3526): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3526): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     ( 3526): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3526): removeSContextService() : service = Auto Rotation
D/SContextService( 3526): ===== SContext Service List =====
D/SContextManager( 3526):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@277efab, service=Auto Rotation
,D/KeyguardViewMediator( 3698): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3698): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3698): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 3698): notifyScreenOffLocked
,V/ActivityThread( 9458): updateVisibility : ActivityRecord{363ce345 token=android.os.BinderProxy@1a7e449a {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PowerManagerService( 3526): Excessive delay in ColorFade : initGLShaders: 22ms
,D/KeyguardViewMediator( 3698): timeout : 5000
,D/KeyguardViewMediator( 3698): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 3698): handleNotifyScreenOff
D/PowerManagerService( 3526): Excessive delay in ColorFade : draw: 19ms
,D/PowerManagerService( 3526): Excessive delay in ColorFade : draw: 14ms
,I/CAE     ( 3526): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     ( 3526): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     ( 3526): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3526): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs( 2869): sendContextData: -76, 13, -47, 0
,D/PowerManagerService( 3526): Excessive delay in ColorFade : draw: 14ms
D/PowerManagerService( 3526): Excessive delay in ColorFade prepare: 122ms
,D/DisplayPowerController( 3526): ColorFade: onAnimationStart
D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3526): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/InputMethodManagerService( 3526): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 3526):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiTrafficPoller( 3526): evaluateTrafficStatsPolling
E/MotionRecognitionService( 3526):  handler : SCREEN_ON end
,I/WifiNative-HAL( 3526): startHal
D/NotificationService( 3526): ACTION_SCREEN_ON
D/LightsService( 3526): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3526) 
D/LightsService( 3526): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,E/wifi    ( 3526): getStaticLongField sWifiHalHandle 0x8fa687fc
D/wifi    ( 3526): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x70206a
D/LightsService( 3526): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
I/WifiNative-HAL( 3526): Could not start hal
D/LightsService( 3526): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/WifiStateMachine( 3526): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3526): handleScreenStateChanged Exit: true
,E/WifiStateMachine( 3526): setSuspendOptimizations: 4 false
E/WifiStateMachine( 3526): mSuspendOptNeedsDisabled 4
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 3526): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 3526): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 3526): Bridge Server is not available
,D/GpsLocationProvider( 3526): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/GpsLocationProvider( 3526): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
,E/GpsLocationProvider( 3526): sExerciseIterface is not available
,I/CheckinService( 4482): Done disabling old GoogleServicesFramework version
,D/PersonaManagerService( 3526): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 3526): MSG_ACTION_SCREEN_ON called
,E/AffinityControl(10487): AffinityControl: registerfunction enter
,I/NfcService( 3969): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/NfcService( 3969): call the applyRouting
,D/AndroidRuntime(10487): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3526): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3526): START PACKAGE DELETE: observer{437306117}
D/PackageManager( 3526): pkg{<packageName>}
D/PackageManager( 3526): user{0}
D/PackageManager( 3526): caller{2000}
D/PackageManager( 3526): flags{3}
D/PersonaManagerService( 3526): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3526): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3526): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3526): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 3526): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3526): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3526): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3526): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3526): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3526): !@killApplicatoin: 10690, uninstall pkg
,D/accuweather( 5276): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5276): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 5276): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
I/ActivityManager( 3526): Force stopping com.example.hello appid=10690 user=-1: uninstall pkg
,I/ActivityManager( 3526): Killing 9458:com.example.hello/u0a690 (adj 0): stop com.example.hello
,I/SamsungIME( 4465): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 5276): [KK AccuPhone]>>> UIM:281 [0:0] update clock event, is not screen on!!
,I/ActivityManager( 3526):   Force finishing activity ActivityRecord{36087241 u0 com.example.hello/.MainActivity t27}
,D/DisplayPowerController( 3526): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3526): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3526): lcd : 0 +
,D/lights  ( 3526): lcd : 0 -
,W/PackageSettings( 3526): Skipping PackageSetting{3bf07833 com.test.thalitest/10689} due to missing metadata
,E/JavaBinder( 3526): !!! FAILED BINDER TRANSACTION !!!
,I/SurfaceFlinger( 2851): id=11 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2851): id=11 Removed NainActivit (-2/8)
,E/JavaBinder( 3526): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 3526): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3526): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3526): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3526): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3526): Force stopping com.example.hello appid=10690 user=0: pkg removed
,D/WifiService( 3526): Client connection lost with reason: 4
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 8023): Explicit concurrent mark sweep GC freed 27179(1545KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 424us total 17.386ms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,W/GeofencerStateMachine( 4202): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4465): mOCRHelper is null
,I/art     ( 4482): Explicit concurrent mark sweep GC freed 55291(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 31MB/47MB, paused 858us total 45.827ms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/InputReader( 3526): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 4056): Explicit concurrent mark sweep GC freed 57878(3MB) AllocSpace objects, 17(2MB) LOS objects, 21% free, 28MB/36MB, paused 770us total 65.170ms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/LWLocationManager(10422): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(10422): getLastUiLocationId() : mLastUiLocationId = -100
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/Zygote  (10524): MountEmulatedStorage()
I/libpersona(10524): KNOX_SDCARD checking this for 10063
E/Zygote  (10524): v2
I/libpersona(10524): KNOX_SDCARD not a persona
,I/SELinux (10524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3526): mCallbacks.updateBrightness()
,D/DisplayPowerState( 3526): !@ ColorFade entry
D/DisplayPowerController( 3526): ColorFade: onAnimationEnd
,I/ActivityManager( 3526): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10524 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AutomaticBrightnessController( 3526): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3526): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,D/TimaKeyStoreProvider(10524): TimaSignature is unavailable
I/AutomaticBrightnessController( 3526): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController( 3526): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/ActivityThread(10524): Added TimaKeyStore provider
I/AutomaticBrightnessController( 3526): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/art     ( 3526): Explicit concurrent mark sweep GC freed 30183(2MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 4.188ms total 109.702ms
D/DisplayPowerController( 3526): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3526): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Sensors ( 3526): Light old sensor_state 513, new sensor_state : 1 en : 0
,D/DisplayPowerController( 3526): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3526): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3526): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3526): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3526): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3526): [PWL] sb release: PowerManagerService.Display
D/SensorManager( 3526): unregisterListener ::   
I/Sensors ( 3526): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/SurfaceFlinger( 2851): Set power mode=0, type=0 flinger=0xb6962000
,I/DisplayManagerService( 3526): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/hwcomposer( 2851): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/SensorManager( 3526): unregisterListener ::   
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(10524): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,W/ResourceType( 4946): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4946): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/VRSetupWizardStub/PackageIntentReceiver(10524): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(10524): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10524): packagename:com.example.hello
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10542): MountEmulatedStorage()
I/libpersona(10542): KNOX_SDCARD checking this for 10021
E/Zygote  (10542): v2
I/libpersona(10542): KNOX_SDCARD not a persona
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SELinux (10542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10542 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/SELinux (10542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 9851:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SecContentProvider2( 3526): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3526): mCursor = null
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Books/Books.apk
,D/EnterpriseDeviceManagerService( 3526): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3526): Admin package name: com.google.android.gms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/PackageManager( 3526): delete codoeFile: 
,D/RegisteredServicesCache( 3969): empty dynamic service
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/AASAUninstall( 3526):  com.example.hello not target!
,D/PackageManager( 3526): result of delete: 1{437306117}
,D/AndroidRuntime(10487): Shutting down VM
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TimaKeyStoreProvider(10542): TimaSignature is unavailable
,D/ActivityThread(10542): Added TimaKeyStore provider
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(10542): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (10542): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 07:25:38 GMT+01:00 2016
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.521: (10542): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3526): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3526): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10542): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (10542): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (10542): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (10542): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/Zygote  (10561): MountEmulatedStorage()
I/libpersona(10561): KNOX_SDCARD checking this for 10106
E/Zygote  (10561): v2
I/libpersona(10561): KNOX_SDCARD not a persona
,I/SELinux (10561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (10542): KLMSIntentService(): PACKAGE_REMOVED
I/SELinux (10561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10561 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (10561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (10542): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10542): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/TimaKeyStoreProvider(10561): TimaSignature is unavailable
,D/ActivityThread(10561): Added TimaKeyStore provider
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3526): PackageReceiver onReceive()
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
I/HarmonyEASService( 3526): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/KnoxMUMContainerPolicy( 3526): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3526): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3526): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3526): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3526): uID is 10690
V/EnterpriseBillingPolicy( 3526): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3526): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3526): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3526): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3526): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3526): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3526): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(10561): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/elm:14491(10561): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(10561): ELMEngine.ELMEngine( context ).
,D/elm:14491(10561): MDMBridge.setEnterpriseBridge()
,E/Zygote  (10577): MountEmulatedStorage()
E/Zygote  (10577): v2
I/libpersona(10577): KNOX_SDCARD checking this for 1000
I/libpersona(10577): KNOX_SDCARD not a persona
,I/SELinux (10577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10577 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 531us total 11.826ms
,W/ResourcesManager(10422): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 276us total 8.779ms
,D/SurfaceControl( 3526): Excessive delay in setPowerMode(): 209ms
D/PowerManagerService( 3526): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL( 3526): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3526): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/TaskPersister( 3526): removeObsoleteFile: deleting file=27_task.xml
,D/PowerManagerService( 3526): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 214ms
,V/ActivityManager( 3526): Display changed displayId=0
,D/TimaKeyStoreProvider(10577): TimaSignature is unavailable
,D/ActivityThread(10577): Added TimaKeyStore provider
D/SSRM:n  ( 3526): SIOP:: AP = 360, PST = 347, CUR = -811
,I/PowerManagerService( 3526): [PWL] Off : 0s ago
,I/PowerManagerService( 3526): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 555us total 9.135ms
,I/KLMS-2.4.521: (10542): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/elm:14491(10561): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/elm:14491(10561): ElmAgentService : onCreate()
,D/elm:14491(10561): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(10561): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10561): MDMBridge.getInstance()
D/elm:14491(10561): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(10561): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (10596): MountEmulatedStorage()
I/libpersona(10596): KNOX_SDCARD checking this for 10052
E/Zygote  (10596): v2
I/libpersona(10596): KNOX_SDCARD not a persona
I/SELinux (10596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=10596 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (10596): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10542): KLMSIntentService(): onDestroy()
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(10577): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(10577): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  (10613): MountEmulatedStorage()
E/Zygote  (10613): v2
I/libpersona(10613): KNOX_SDCARD checking this for 10019
I/libpersona(10613): KNOX_SDCARD not a persona
,I/SELinux (10613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10613): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10613 uid=10019 gids={50019, 9997} abi=armeabi-v7a
D/TimaKeyStoreProvider(10596): TimaSignature is unavailable
,D/ActivityThread(10596): Added TimaKeyStore provider
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/elm:14491(10561): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider(10613): TimaSignature is unavailable
,D/ActivityThread(10613): Added TimaKeyStore provider
,W/ResourceType( 3526): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/RCPManager(10577):  in createShortcut() for packageName: com.example.hello userId0
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 3526):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3526): queryAllProviders():  providerCallBack is not register for 0
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(10596): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager(10422): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(10245): onReceive()
W/fb4a(:<default>):QeInternalImpl( 9793): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/TapandpayWidget:TanpandpayAppWidgetProvider(10245): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
W/ResourcesManager(10422): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10422): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10422): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10422): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/TapandpayWidget:Utils(10245): Clear T&P info.
W/ResourcesManager(10596): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10596): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10596): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10596): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10596): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TapandpayWidget:TanpandpayAppWidgetProvider(10245): Widget is not attached.
D/ResourcesManager(10613): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(10422): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 3526): Killing 9830:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3526): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3526): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,E/Zygote  (10632): MountEmulatedStorage()
E/Zygote  (10632): v2
I/libpersona(10632): KNOX_SDCARD checking this for 10101
D/ResourcesManager(10422): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/libpersona(10632): KNOX_SDCARD not a persona
,I/SELinux (10632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10632 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 8770:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,I/SELinux (10632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Killing 9891:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,W/fb4a(:<default>):UserScope( 9793): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/SELinux (10632): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10613): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10613): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10613): onReceive() : package name is not s health. Return !!!
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/SystemBroadcastReceiver(10299): [#DCM#] [DCM_Performance] onReceive completed in time  304 microsec. 
,D/LocationWidgetApplication(10422): getLastUiLocationId() : mLastUiLocationId = -100
I/SystemBroadcastReceiver(10299): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10299): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController(10299): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/PackageBroadcastService( 4482): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 4482): Clearing selected account for com.example.hello
,D/TimaKeyStoreProvider(10632): TimaSignature is unavailable
,D/ActivityThread(10632): Added TimaKeyStore provider
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/Mms/MmsApp(10596): [start]    onCreate() consume time = 0.0
,I/LocationSettingsChecker( 4482): Removing dialog suppression flag for package com.example.hello
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/Mms/ArtClassLoader(10596): init before art
,D/Mms/ArtClassLoader(10596): init [DONE] art
,I/art     ( 9793): Thread[1,tid=9793,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/gH_CompatibleDatabase( 4482): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4482): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4482): 0 metrics were deleted when clearing package com.example.hello.
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/gH_CompatibleDatabase( 4482): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9793): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(10632): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/gH_CompatibleDatabase( 4482): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 4482): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 4482): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/ResourcesManager(10422): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/gH_CompatibleDatabase( 4482): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4482): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 4482): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/UsbSettingsManager( 3526): clearDefaults: com.example.hello
I/CrashAnrDetector( 3526): onPackageRemoved : com.example.hello
D/gH_CompatibleDatabase( 4482): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 4482): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 4482): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/Mms/TelephonyPermission(10596): start operation mode monitor
,D/LightsService( 3526): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 3526) 
D/LightsService( 3526): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,I/Sensors ( 3526): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3526): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService( 3526): turn on LED for charging
,D/ResourcesManager(10596): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10596): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10422): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/Zygote  (10655): MountEmulatedStorage()
E/Zygote  (10655): v2
I/libpersona(10655): KNOX_SDCARD checking this for 1000
I/libpersona(10655): KNOX_SDCARD not a persona
,I/ActivityManager( 3526): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10655 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 9810:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,I/SELinux (10655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Mms/TelephonyPermission(10596): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(10596): isDefault true
,E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearPendingStateOp( 4482): Runtime exception while performing operation
E/ClearPendingStateOp( 4482): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4482): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4482): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4482): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 4482): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4482): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4482): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4482): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4482): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 4482): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4482): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4482): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4482): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4482): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4482): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 4482): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 4482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 4482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 4482): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4482): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4482): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 4482): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 4482): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 4482): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,I/SELinux (10655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4482): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/Mms/MmsApp(10596): onCreate() com.android.mms
,D/DocsApplication(10632): Installing DEX configuration.
,I/CAE     ( 3526): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     ( 3526): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3526): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3526): SendSensorHubData: send data = -76, 13, -46, 0
,D/DexInstaller(10632): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/Sensorhubs( 2869): sendContextData: -76, 13, -46, 0
I/PackageInfoHelper(10632): Provided clientMode=RELEASE, packageInfo=PackageInfo{81f61bc com.google.android.apps.docs}
,D/TAG     (10632): onCreate()
,I/CAE     ( 3526): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 6, 25, 38,
D/SensorHubManager( 3526): SendSensorHubData: send data = -63, 14, 6, 25, 38
,D/Sensorhubs( 2869): sendContextData: -63, 14, 6, 25, 38
,D/CrossAppStateProvider(10632): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,W/InputMethodManagerService( 3526): Got RemoteException sending setActive(false) notification to pid 9458 uid 10690
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/Mms/MmsApp(10596): [start]    initCountryIso consume time = 134.730208
,D/CountryDetector( 3526): The first listener is added
,D/TimaKeyStoreProvider(10655): TimaSignature is unavailable
D/ActivityThread(10655): Added TimaKeyStore provider
,D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3526): displayNotification : [02h,02h,01h]
,D/MotionRecognitionService( 3526):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3526): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
,D/UsbHostManager( 3526): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3526): displayNotification : [0ah,00h,01h]
,D/Mms/MmsApp(10596): [end]    initCountryIso consume time = 8.646333
D/Mms/MmsConfig(10596): [start]    MmsConfig.init() consume time = 0.071584
E/AndroidRuntime( 4482): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 4482): Process: com.google.android.gms, PID: 4482
E/AndroidRuntime( 4482): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 4482): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 4482): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 4482): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 4482): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 4482): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4482): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4482): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/UsbHostManager( 3526): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3526): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3526): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/ResourcesManager(10422): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/Mms/MmsConfig(10596): before partial update
,E/SQLiteLog( 4202): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4202): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4202): Shutting down VM
,E/MotionRecognitionService( 3526):  handler : SCREEN_OFF end 
D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Books/Books.apk
,V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/AndroidRuntime( 4202): FATAL EXCEPTION: main
E/AndroidRuntime( 4202): Process: com.google.android.gms.persistent, PID: 4202
E/AndroidRuntime( 4202): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4202): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4202): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4202): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4202): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4202): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4202): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4202): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4202): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4202): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4202): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4202): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4202): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4202): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4202): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4202): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4202): 	... 9 more
,D/Mms/MmsConfig(10596): Load Resize quality : 80
I/WifiTrafficPoller( 3526): evaluateTrafficStatsPolling
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4482): Module APK com.google.android.play.games already loaded
,I/Icing   ( 4482): doRemovePackageData com.example.hello
,D/Mms/MmsConfig(10596):  enable multiwindow = true
,E/DropBoxManagerService( 3526): Can't write: system_app_wtf
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/Process ( 4482): Sending signal. PID: 4482 SIG: 9
,D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3526): displayNotification : [09h,00h,00h]
,V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,D/ResourcesManager(10655): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,E/DropBoxManagerService( 3526): Can't write: system_app_crash
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,I/WifiNative-HAL( 3526): startHal
E/wifi    ( 3526): getStaticLongField sWifiHalHandle 0x8fa687fc
D/wifi    ( 3526): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x901f7e
I/WifiNative-HAL( 3526): Could not start hal
D/WifiStateMachine( 3526): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3526): handleScreenStateChanged Exit: false
,E/WifiStateMachine( 3526): setSuspendOptimizations: 4 true
E/WifiStateMachine( 3526): mSuspendOptNeedsDisabled 0
,W/ActivityManager( 3526): Process com.google.android.gms has crashed too many times: killing!
,E/DropBoxManagerService( 3526): Can't write: system_app_crash
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,I/ActivityManager( 3526): Killing 4202:com.google.android.gms.persistent/u0a14 (adj 0): crash
,D/UsbHostManager( 3526): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3526): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/PCWCLIENTTRACE_LOG(10655): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10655): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10655): new DMDBOpenHelper instance
,E/SQLiteLog(10655): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/Mms/MessageUtils(10596): setCountryDetector : update country detector info 
E/Mms/MessageUtils(10596): updateCountryIso : update country iso info 
E/SQLiteDatabase(10655): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10655): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10655): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10655): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10655): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10655): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10655): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10655): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10655): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10655): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10655): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10655): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10655): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10655): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10655): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10655): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10655): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10655): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10655): Shutting down VM
,E/AndroidRuntime(10655): FATAL EXCEPTION: main
E/AndroidRuntime(10655): Process: com.sec.pcw.device, PID: 10655
E/AndroidRuntime(10655): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10655): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10655): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10655): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10655): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10655): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10655): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10655): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10655): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10655): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10655): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10655): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10655): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10655): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10655): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10655): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10655): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10655): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10655): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10655): 	... 11 more
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/EventHub( 3526): Removing device '/dev/input/event10' due to inotify event
,V/BackupManagerService( 3526): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3526): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,D/NotificationService( 3526): ACTION_SCREEN_OFF
,D/LightsService( 3526): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3526) 
D/LightsService( 3526): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
,V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/MtpClient(10359): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(10359): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/Mms/PackageInfo(10596): com.sec.imsservice is not installed
D/Mms/MmsConfig(10596): [end]    init() consume time = 136.966166
,W/BroadcastQueue( 3526): Unable to launch app com.google.android.gms/10014 for broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }: process is bad
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=off)
,I/EventHub( 3526): Removing device '/dev/input/event7' due to inotify event
,D/Mms/Contact(10596): [start]    init() consume time = 10.651625
,E/DropBoxManagerService( 3526): Can't write: system_app_crash
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop184.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/Mms/Contact(10596): [end]    init consume time = 29.105834
,D/Mms/DraftCache(10596): [start]    rebuildCache consume time = 7.027833
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,E/Zygote  (10696): MountEmulatedStorage()
E/Zygote  (10696): v2
I/libpersona(10696): KNOX_SDCARD checking this for 10035
W/art     ( 9793): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
I/libpersona(10696): KNOX_SDCARD not a persona
,I/SELinux (10696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10696): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=10696 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/EventHub( 3526): Removing device '/dev/input/event8' due to inotify event
,D/LocationManagerService( 3526): Location listener died
,D/WifiService( 3526): Client connection lost with reason: 4
D/LocationManagerService( 3526): Location listener died
,D/GpsStatusListenerHelper( 3526): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@6d3a03a
,I/LocationManagerService( 3526): remove 31beaabc by com.google.android.gms
,D/LocationManagerService( 3526): provider request: passive ProviderRequest[ON interval=0]
,D/PowerManagerService( 3526): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10014, pid=4482, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=220)
D/ConnectivityService( 3526): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@9c914eb)
,D/ConnectivityService( 3526): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/LocationManagerService( 3526): remove 3a587868 by com.google.android.gms
,D/LocationManagerService( 3526): provider request: passive ProviderRequest[ON interval=0]
,E/ConnectivityService( 3526): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/EventHub( 3526): Removing device '/dev/input/event9' due to inotify event
I/Process (10655): Sending signal. PID: 10655 SIG: 9
,I/ActivityManager( 3526): Process com.google.android.gms (pid 4482)(adj 0) has died(305,1210)
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10998ms
,I/EventHub( 3526): Removing device '/dev/input/event11' due to inotify event
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10992ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10990ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20988ms
W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 30986ms
,D/TP/MmsSmsProvider( 3982): query,matched:12, calling pid = 10596
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,I/SecExternalDisplayIntents_Java( 3526): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/Mms/TelephonyUtils(10596): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(10596): roaming -> false (slotId = 0)
D/Mms/DownloadManager(10596): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10596): auto download without roaming -> true
D/Mms/DownloadManager(10596): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(10596): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(10596): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(10596): roaming -> false (slotId = 1)
D/Mms/DownloadManager(10596): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(10596): auto download without roaming -> true
D/Mms/DownloadManager(10596): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(10596): auto download during roaming secondary -> false
D/Mms/DownloadManager(10596): mAutoDownload ------> true
D/TP/MmsSmsProvider( 3982): match 12:Elapsed time : 32.557 ms
,D/TimaKeyStoreProvider(10696): TimaSignature is unavailable
D/TP/MmsSmsProvider( 3982): query,matched:13, calling pid = 10596
,D/ActivityThread(10696): Added TimaKeyStore provider
,I/EventHub( 3526): Removing device '/dev/input/event12' due to inotify event
,D/TP/MmsSmsProvider( 3982): match 13:Elapsed time : 17.313 ms
,D/Mms/Conversation(10596): [start]    init() consume time = 188.425292
,D/Mms/MmsApp(10596): [end]    onCreate() consume time = 9.773375
,D/Mms/DraftCache(10596): [end]    rebuildCache consume time = 9.975125
,D/IpRemoteDisplayController( 3526): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 3526): Bridge Server is not available
,I/ActivityManager( 3526): Process com.sec.pcw.device (pid 10655)(adj 9) has died(303,1210)
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/Mms/FreeMessageStatusReceiver(10596): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/EventHub( 3526): Removing device '/dev/input/event13' due to inotify event
,D/TP/MmsSmsProvider( 3982): deleteConversation threadId: 9223372036854775807
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/SSRM:a  ( 3526): DeviceInfo:: 000000100000
,D/SSRM:a  ( 3526): SettingsAirViewInfo:: 000000000
,D/ResourcesManager(10696): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/EventHub( 3526): Removing device '/dev/input/event14' due to inotify event
,D/Mms/DownloadManager(10596): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/VolumePanel( 3698): registerReceiver: onReceive start 
D/VolumePanel( 3698): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3698): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3698): registerReceiver: onReceive end 
D/Mms/DownloadManager(10596): roaming ------> false, mSimSlot = 0
,D/Mms/TelephonyUtils(10596): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(10596): roaming -> false (slotId = 0)
,D/Mms/DownloadManager(10596): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10596): auto download without roaming -> true
,D/Mms/DownloadManager(10596): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(10596): mAutoDownload ------> true
,D/ResourcesManager(10422): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/Mms/FreeMessageReceiverService(10596): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(10596): onHandleIntent: ACTION_PACKAGE_REMOVED
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10717): MountEmulatedStorage()
E/Zygote  (10717): v2
I/libpersona(10717): KNOX_SDCARD checking this for 1000
D/ResourcesManager(10422): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
I/libpersona(10717): KNOX_SDCARD not a persona
,I/SELinux (10717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27,
,I/SELinux (10717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=10717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/VolumePanel( 3698): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/VolumePanel( 3698): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 3698): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3698): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3698): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,I/FeatureConfig(10696): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]

```
