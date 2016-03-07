#### Test 6170335106d974e_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
D/ResourcesManager( 8346): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 8346): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 8346): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager( 8881): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/ResourcesManager( 8346): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/System.out( 3524): AsyncTask #5 calls detatch()
W/System.err( 3524): java.io.IOException: Not Found
W/System.err( 3524): 	at a.d.b(Unknown Source)
W/System.err( 3524): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3524): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3524): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3524): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3524): 	at java.lang.Thread.run(Thread.java:818)
,D/ResourcesManager( 8346): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
D/ResourcesManager( 8346): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
--------- beginning of system
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/System.out( 9188): P[5]_NetworkDispatch1 calls detatch()
I/ActivityManager( 3524): Killing 8346:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
V/DownloadManager( 5321): onReceive intent + android.intent.action.UID_REMOVED
W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{24b866a4 u0 ReceiverList{23f4b137 9188 com.facebook.appmanager/10110/u0 remote:3d6e0e36}}
W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{24b866a4 u0 ReceiverList{23f4b137 9188 com.facebook.appmanager/10110/u0 remote:3d6e0e36}}
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 9388): MountEmulatedStorage()
I/libpersona( 9388): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9388): v2
I/libpersona( 9388): KNOX_SDCARD not a persona
I/SELinux ( 9388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=9388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{54cae0e u0 ReceiverList{39d2c09 9188 com.facebook.appmanager/10110/u0 remote:21674910}}
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/TimaKeyStoreProvider( 9388): TimaSignature is unavailable
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ActivityThread( 9388): Added TimaKeyStore provider
D/ResourcesManager( 9388): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
E/MTPRx   ( 9388): In MtpReceiverandroid.hardware.usb.action.USB_STATE
D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
D/SecContentProvider2( 3524): mCursor = null
D/SecContentProvider2( 3524): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 3524): mCursor = null
V/MTPRx   ( 9388): sealedState: false
V/MTPRx   ( 9388): sealedUsbMassStorageState: false
E/MTPRx   ( 9388): check value of boot_completed is1
E/MTPRx   ( 9388): check booting is completed_sys.boot_completed
E/MTPRx   ( 9388): Sd-Card path/storage/extSdCard
E/MTPRx   ( 9388): Status for mount/Unmount :removed
E/MTPRx   ( 9388): SDcard is not available
W/MTPRx   ( 9388): value of connected istrue
W/MTPRx   ( 9388): value of configured istrue
W/MTPRx   ( 9388): value of mtpEnabled isfalse
W/MTPRx   ( 9388): value of ptpEnabled istrue
E/MTPRx   ( 9388): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 9388): mFirstTime: false
D/        ( 9388): MTP: reading debug level property
E/MTPJNIInterface( 9388): Getting CryptionKey from JAVA
E/MTPRx   ( 9388): currentUserId is 0
E/MTPRx   ( 9388): Start observing USB_STATE_MATCH 
D/AndroidRuntime( 9377): 
D/AndroidRuntime( 9377): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/MTPRx   ( 9388): usbMode is 0200
E/MTPRx   ( 9388): is_Privatemode is NOT 1
D/AndroidRuntime( 9377): CheckJNI is OFF
D/AndroidRuntime( 9377): readGMSProperty: start
D/AndroidRuntime( 9377): readGMSProperty: already setted!!
D/SettingsProvider( 3524): name = boot_time_connected
D/AndroidRuntime( 9377): readGMSProperty: end
D/AndroidRuntime( 9377): addProductProperty: start
E/MTPRx   ( 9388): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 9388): noti = 17
D/SettingsProvider( 3524): name = mtp_usb_conditions_met
D/SecContentProvider( 3524): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 9388): sending PTP_ICON_ENABLED to stack 
D/SettingsProvider( 3524): name = mtp_running_status
D/SettingsProvider( 3524): name = mtp_usb_conditions_met
E/MTPRx   ( 9388): else part ... so first time!!!
E/MTPPlaObsrvr( 9388): inside setContext()
E/MTPPlaObsrvr( 9388):  inside createplafiles
E/MTPPlaObsrvr( 9388): playlist count is0
E/MTPPlaObsrvr( 9388):  inside try branch createplafiles
E/MTPPlaObsrvr( 9388):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 9388): Inside registerContentObserver
E/MtpAdbObserver( 9388): inside setContext()
E/MtpAdbObserver( 9388): Inside registerContentObserver
W/Settings( 9388): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
D/SettingsProvider( 3524): name = mtp_running_status
D/SettingsProvider( 3524): name = mtp_usb_conditions_met
E/MtpService( 9388): onCreate.
E/MtpService( 9388): < MTP > Registering BroadCast receiver :::::
E/MtpService( 9388): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 9388): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
W/MTPRx   ( 9388): calling native method
E/MTPJNIInterface( 9388): < MTP > Registering BroadCast receiver :::::
E/MTPJNIInterface( 9388): < MTP > Registering BroadCast receiver :::::::
D/MtpService( 5321): updating state; isCurrentUser=true, mMtpLocked=false
E/MTPJNIInterface( 9388): noti = 11
E/MtpService( 9388): onStartCommand.
E/MtpService( 9388): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 9388): calling native method
E/MTPRx   ( 9388): Checking the driver time out
E/MTPJNIInterface( 9388): noti = 2
D/        ( 9388): deleting sockets before message queue initialization
D/        ( 9388): event handler thread is created, so set the flag
E/MTPRx   ( 9388): called native method
E/MTPJNIInterface( 9388): setting Media scanner status0
E/MTPJNIInterface( 9388): After setting Media scanner status0
E/MtpService( 9388): onStartCommand.
E/MtpService( 9388): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 9388): notification from stack 1
E/        ( 9388): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 9388): Getting media scanner status0
E/MTPJNIInterface( 9388): DeviceName is Note4-1
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (4/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9417): MountEmulatedStorage()
E/Zygote  ( 9417): v2
I/libpersona( 9417): KNOX_SDCARD checking this for 1000
I/libpersona( 9417): KNOX_SDCARD not a persona
I/SELinux ( 9417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=9417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 9417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9417): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/AffinityControl( 9377): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 9417): TimaSignature is unavailable
D/ActivityThread( 9417): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8782(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 901us total 21.764ms
D/AndroidRuntime( 9377): Calling main entry com.android.commands.am.Am
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 616us total 10.948ms
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
D/ResourcesManager( 9417): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 330us total 9.855ms
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@2
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3524): mDVFSHelper.acquire()
D/PermissionCache( 2849): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (163 us)
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, iello
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIInstallConfirmActivity(394/onUserLeaveHint)] 
I/DBG_DM  ( 6311): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 17
D/AndroidRuntime( 9377): Shutting down VM
I/DBG_DM  ( 6311): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 6311): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIInstallConfirmActivity(399/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
I/DBG_DM  ( 6311): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/TMNetworkReceiver( 9417): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive() Exit 
D/TMSLogRemovalReceiver( 9417): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver( 9417): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 9417): TMLogRemovalReceiver.onReceive() Exit
I/ActivityManager( 3524): Killing 8790:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
D/TMNetworkReceiver( 9417): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
I/DBG_DM  ( 6311): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
V/UserPresentBroadcastReceiver( 4652): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3524): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
D/SecContentProvider2( 3524): mCursor = null
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/ApplicationPolicy( 3524): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager( 3524): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 6311): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
D/PanelView( 3695): There is/are notification(s) 
I/DBG_DM  ( 6311): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
D/PanelView( 3695): There is/are notification(s) 
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/PanelView( 3695): There is/are notification(s) 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/KnoxNotification( 3695): ----- inflateViews : modified publicViewLocal -----
E/Zygote  ( 9441): MountEmulatedStorage()
I/libpersona( 9441): KNOX_SDCARD checking this for 10678
E/Zygote  ( 9441): v2
I/libpersona( 9441): KNOX_SDCARD not a persona
I/SELinux ( 9441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9441): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9441 uid=10678 gids={50678, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/KnoxNotification( 3695): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 3695): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3695): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@1250dff2
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 9441): TimaSignature is unavailable
D/ActivityThread( 9441): Added TimaKeyStore provider
E/Zygote  ( 9453): MountEmulatedStorage()
E/Zygote  ( 9453): v2
I/libpersona( 9453): KNOX_SDCARD checking this for 10022
I/libpersona( 9453): KNOX_SDCARD not a persona
I/SELinux ( 9453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=9453 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PanelView( 3695): There is/are notification(s) 
D/PanelView( 3695): There is/are notification(s) 
D/TimaKeyStoreProvider( 9453): TimaSignature is unavailable
D/ActivityThread( 9453): Added TimaKeyStore provider
D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/PanelView( 3695): There is/are notification(s) 
D/PanelView( 3695): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/ResourcesManager( 9441): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/ResourcesManager( 9453): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
W/ResourcesManager( 9453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9453): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/hwcutils( 2849): MppFactory::MppFactory()
D/        ( 2849): virtual LibMpp* MppFactory::CreateMpp(int, int, int, int) dev(4) mode(0) drm(0), 
D/libexynosgscaler( 2849): LibMpp::LibMpp()
I/LocationWidgetApplication( 9453): onCreate() : start
D/LocationWidgetApplication( 9453): countryCode = POLAND
D/BluetoothNotiBroadcastReceiver( 8912): onReceive
I/ActivityManager( 3524): Killing 8823:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/PanelView( 3695): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/WebViewFactory( 9441): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
I/ActivityManager( 3524): Waited long enough for: ServiceRecord{260dd489 u0 com.sec.android.app.SmartClipService/com.samsung.android.service.hermes.HermesServiceStarter}
I/ActivityManager( 3524): Waited long enough for: ServiceRecord{159b6c8e u0 com.sec.android.app.SmartClipService/com.samsung.android.service.hermes.HermesCollectorService}
D/ResourcesManager( 9441): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 9441): Loading: webviewchromium
I/LibraryLoader( 9441): Time to load native libraries: 3 ms (timestamps 8077-8080)
I/LibraryLoader( 9441): Expected native library version number "",actual native library version number ""
D/AuthorizationBluetoothService( 4652): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9474): MountEmulatedStorage()
E/Zygote  ( 9474): v2
I/libpersona( 9474): KNOX_SDCARD checking this for 10047
I/libpersona( 9474): KNOX_SDCARD not a persona
I/SELinux ( 9474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9474): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=9474 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 9474): TimaSignature is unavailable
D/ActivityThread( 9474): Added TimaKeyStore provider
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9188): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
V/WebViewChromiumFactoryProvider( 9441): Binding Chromium to main looper Looper (main, tid 1) {db07d31}
I/LibraryLoader( 9441): Expected native library version number "",actual native library version number ""
I/chromium( 9441): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/ResourcesManager( 9474): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
W/ResourcesManager( 9474): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9188): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
I/BrowserStartupController( 9441): Initializing chromium process, renderers=0
W/art     ( 9441): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 9441): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 9441): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 9441): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/appmanager(:<default>):QuickExperimentControllerImpl( 9188): Exposure of experiment com.facebook.imagepipeline.m.d@2ae7c9c7 occurred when no user was logged in
I/CalendarProvider2( 9474): CalendarProvider2.onCreate() called
W/appmanager(:<default>):aa( 9188): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
W/appmanager(:<default>):aa( 9188): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
V/analytics4a( 9188): JNI_OnLoad called
V/analytics4a( 9188): JNI_OnLoad complete
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/art     ( 9188): Explicit concurrent mark sweep GC freed 60760(3MB) AllocSpace objects, 6(119KB) LOS objects, 22% free, 28MB/36MB, paused 742us total 35.649ms
W/appmanager(:<default>):m( 9188): No feature status reporters found; is this dead code?
I/art     ( 3524): Explicit concurrent mark sweep GC freed 63004(3MB) AllocSpace objects, 3(185KB) LOS objects, 22% free, 53MB/69MB, paused 1.674ms total 109.156ms
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9529): MountEmulatedStorage()
E/Zygote  ( 9529): v2
I/libpersona( 9529): KNOX_SDCARD checking this for 1000
I/libpersona( 9529): KNOX_SDCARD not a persona
I/SELinux ( 9529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/chromium( 9441): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/ActivityManager( 3524): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=9529 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/chromium( 9441): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
E/SQLiteLog( 9474): (284) automatic index on view_events(_id)
W/art     ( 9441): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 9529): TimaSignature is unavailable
D/ActivityThread( 9529): Added TimaKeyStore provider
W/AwContents( 9441): onDetachedFromWindow called when already detached. Ignoring
D/CalendarAlarmManager( 9474): sys current time:1457358126134
D/CalendarAlarmManager( 9474): reminder amount:0
D/ResourcesManager( 9529): creating new AssetManager and set to /system/priv-app/DeviceTest/DeviceTest.apk
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/ResourcesManager( 9529): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 9441): CordovaWebView is running on device made by: samsung
W/art     ( 9441): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 9441): Attempt to remove local handle scope entry from IRT, ignoring
D/FactoryTestApp( 9529): [ProtectedFactoryTestBroadcastReceiver$onReceive](9529) onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 9529): [ProtectedFactoryTestBroadcastReceiver$onReceive](9529) android.intent.action.SECPHONE_READY
D/FactoryTest( 9529): User mode
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9554): MountEmulatedStorage()
I/libpersona( 9554): KNOX_SDCARD checking this for 10021
E/Zygote  ( 9554): v2
I/libpersona( 9554): KNOX_SDCARD not a persona
I/SELinux ( 9554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.ContainerReceiver: pid=9554 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
D/Activity( 9441): performCreate Call secproduct feature valuefalse
D/Activity( 9441): performCreate Call debug elastic valuetrue
I/ActivityManager( 3524): Killing 8844:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
D/TimaKeyStoreProvider( 9554): TimaSignature is unavailable
D/ActivityThread( 9554): Added TimaKeyStore provider
D/ResourcesManager( 9554): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: ( 9554): KLMSAbstractReciever(): onReceive(): Intent { act=com.samsung.action.knox.kap.KAP_NOTIFICATION flg=0x10 pkg=com.samsung.klmsagent cmp=com.samsung.klmsagent/.listner.ContainerReceiver (has extras) } | timestamp: Mon Mar 07 14:42:06 GMT+01:00 2016
D/libexynosgscaler( 2849): virtual CGscaler::~CGscaler()
D/libexynosgscaler( 2849): virtual LibMpp::~LibMpp()
D/        ( 2849): virtual MppFactory::~MppFactory()
D/OpenGLRenderer( 9441): Render dirty regions requested: true
I/KLMS-2.4.521: ( 9554): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: ( 9554): KLMSIntentService(): onCreate()
I/ActivityManager( 3524): Waited long enough for: ServiceRecord{3969cf76 u0 com.trustonic.tuiservice/.TuiService}
I/KLMS-2.4.521: ( 9554): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/MTPJNIInterface( 9388): Status for mount/Unmount :removed
E/MTPJNIInterface( 9388): SDcard is not available
I/KLMS-2.4.521: ( 9554): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: ( 9554): KLMSIntentService(): onHandleIntent().START: Intent { act=com.samsung.action.knox.kap.KAP_NOTIFICATION flg=0x10 pkg=com.samsung.klmsagent cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: ( 9554): KLMSIntentService(): RP_MODE_NOTIFY
I/KLMS-2.4.521: ( 9554): B2C-ContainerStateImpl(): uploadRPMode().Start.
I/KLMS-2.4.521: ( 9554): B2C-ContainerStateImpl(): checkKNOXLicenseStatus().No activation record is found when container license check came.
E/        ( 9388): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
E/Zygote  ( 9576): MountEmulatedStorage()
E/Zygote  ( 9576): v2
I/libpersona( 9576): KNOX_SDCARD checking this for 10160
I/libpersona( 9576): KNOX_SDCARD not a persona
I/SELinux ( 9576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9576): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.control.ui.quickmemo.receiver.PenGestureReceiver: pid=9576 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
E/MTPJNIInterface( 9388): Status for mount/Unmount :removed
E/MTPJNIInterface( 9388): SDcard is not available
E/SQLiteLog( 9388): (21) API call with NULL database connection pointer
E/SQLiteLog( 9388): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog( 9388): (21) API call with NULL database connection pointer
E/SQLiteLog( 9388): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9388): (21) API call with NULL database connection pointer
E/SQLiteLog( 9388): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9388): (21) API call with NULL database connection pointer
E/SQLiteLog( 9388): (21) misuse at line 105958 of [9491ba7d73]
W/MTPRx   ( 9388): notification from stack 2
D/        ( 9388): [mtp_init_device] Library open with 32 bits.
D/        ( 9388): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 9388): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        ( 9388): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 9388):  [sua_support_present:1277] returning false 
D/        ( 9388): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
D/TimaService( 3524): BroadcastReceiver - action:  com.samsung.action.knox.klms.KLMS_RP_NOTIFICATION
D/TimaService( 3524): handleLicenseStatus - notiTrigger: 3, licenseStatus: false
I/KLMS-2.4.521: ( 9554): KLMSIntentService(): onDestroy()
I/ActivityManager( 3524): Killing 8756:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31

```
