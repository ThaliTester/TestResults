#### Test 9691894766ea5e0_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
12-07 15:37:56.476  9208  9208 E Zygote  : v2
12-07 15:37:56.476  9208  9208 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-07 15:37:56.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:37:56.476  9208  9208 E Zygote  : accessInfo : 0
--------- beginning of system
12-07 15:37:56.476  9208  9208 I libpersona: KNOX_SDCARD checking this for 1000
12-07 15:37:56.476  9208  9208 I libpersona: KNOX_SDCARD not a persona
12-07 15:37:56.476  3463  4326 I ActivityManager: Start proc 9208:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.service.ContextAgentReceiver
12-07 15:37:56.486  9208  9208 D TimaKeyStoreProvider: TimaSignature is unavailable
12-07 15:37:56.486  9208  9208 D ActivityThread: Added TimaKeyStore provider
12-07 15:37:56.496  9208  9208 D RelationGraph: garbageCollect()
12-07 15:37:56.496  9208  9208 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-07 15:37:56.496  3463  3492 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97d8dbf u0 com.samsung.android.sm.ACTION_LOGGING_ABNORMAL_APP_LIST qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c5fbc8c 9208:com.samsung.android.sm/1000}
12-07 15:37:56.496  9208  9208 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-07 15:37:56.496  9208  9208 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_NoIcon/SmartManager_v3_NoIcon.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
12-07 15:37:56.496  3463  4063 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-07 15:37:56.506  9208  9208 I InjectionManager: Inside getClassLibPath caller 
12-07 15:37:56.506  9208  9208 D ResourcesManager: For user 0 new overlays fetched Null
12-07 15:37:56.516  9208  9208 D InjectionManager: InjectionManager
12-07 15:37:56.516  9208  9208 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
12-07 15:37:56.516  9208  9208 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
12-07 15:37:56.516  9208  9208 I InjectionManager: featureStore :{}
12-07 15:37:56.516  9208  9208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 com.samsung.android.sm.base.b.a:473 com.samsung.android.sm.service.ContextAgentReceiver.onReceive:139 android.app.ActivityThread.handleReceiver:3635 
12-07 15:37:56.516  3463  3974 I ActivityManager: Killing 8693:com.policydm/1000 (adj 15): DHA:empty #33
12-07 15:37:56.526  3463  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7e1fd5 u0 com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98f7ff4 8650:com.google.android.talk/u0a117}
12-07 15:37:56.536  8624  8624 I ServiceUtils: [StoryService] getSharedPrefLong retVal: 2 
12-07 15:37:56.536  8624  8624 I ServiceUtils: [StoryService] setSharedPrefLong : 2 
12-07 15:37:56.536  3463  4339 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58746db u0 com.samsung.storyservice.eventUpgrade qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5268deb 8624:com.samsung.storyservice/5004}
12-07 15:37:56.546  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@6be33b4 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:56.546  3463  4063 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
12-07 15:37:56.546  3463  4339 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a921578 u0 com.google.android.music.IMPORT_COMPLETE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8be16c 5399:com.google.android.music:main/u0a128}
12-07 15:37:56.566  8650  8650 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,12-07 15:37:56.586  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
12-07 15:37:56.586  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:56.586  5399  5399 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
12-07 15:37:56.596  5399  9226 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
12-07 15:37:56.596  9227  9227 E Zygote  : v2
12-07 15:37:56.596  9227  9227 I libpersona: KNOX_SDCARD checking this for 10144
12-07 15:37:56.596  9227  9227 I libpersona: KNOX_SDCARD not a persona
12-07 15:37:56.596  9227  9227 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-07 15:37:56.596  9227  9227 E Zygote  : accessInfo : 0
12-07 15:37:56.596  3463  3492 I ActivityManager: Start proc 9227:com.android.calendar/u0a144 for broadcast-3 com.android.calendar/.edge.EdgeService$CalendarFactory
12-07 15:37:56.596  9227  9227 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.calendar 
12-07 15:37:56.606  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
12-07 15:37:56.606  9227  9227 D TimaKeyStoreProvider: TimaSignature is unavailable
12-07 15:37:56.606  9227  9227 D ActivityThread: Added TimaKeyStore provider
12-07 15:37:56.606  4866  8983 I qtaguid : Untagging socket 43
12-07 15:37:56.616  3463  3857 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f1124 u0 com.sec.android.intent.UPDATE_EDGE_PANEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb748d 9227:com.android.calendar/u0a144}
12-07 15:37:56.626  9227  9227 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-07 15:37:56.626  9227  9227 D RelationGraph: garbageCollect()
12-07 15:37:56.626  9227  9227 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.android.calendar rsrc of package com.android.calendar
12-07 15:37:56.626  3463  4989 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-07 15:37:56.626  9227  9227 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-07 15:37:56.626  9227  9227 D ResourcesManager: For user 0 new overlays fetched Null
12-07 15:37:56.626  9227  9227 I InjectionManager: Inside getClassLibPath caller 
12-07 15:37:56.636  9227  9227 W System  : ClassLoader referenced unknown path: /system/app/SPlanner_M/lib/arm64
12-07 15:37:56.636  9227  9227 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.android.calendar rsrc of package com.android.calendar
12-07 15:37:56.646  9227  9227 D InjectionManager: InjectionManager
12-07 15:37:56.646  9227  9227 D InjectionManager: fillFeatureStoreMap com.android.calendar
12-07 15:37:56.646  9227  9227 I InjectionManager: Constructor com.android.calendar, Feature store :{}
12-07 15:37:56.646  9227  9227 I InjectionManager: featureStore :{}
12-07 15:37:56.656  3463  4990 I ActivityManager: Killing 8708:com.sec.android.soagent/1000 (adj 15): DHA:empty #33
12-07 15:37:56.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:37:56.656  3463  4990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa1c642 u0 com.android.mms.intent.action.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47287ef 5962:com.android.mms/u0a55}
12-07 15:37:56.656  4866  8983 I qtaguid : Untagging socket 50
12-07 15:37:56.666  4866  8983 D DownloadManager: [1181] Finished with status SUCCESS
12-07 15:37:56.666  4866  8983 V DownloadManager: MIME Type = application/octet-stream
12-07 15:37:56.676  3463  4443 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a55b653 u0 com.android.mms.intent.action.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47287ef 5962:com.android.mms/u0a55}
12-07 15:37:56.686  3463  3493 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
12-07 15:37:56.686  4866  8981 V DownloadManager: 1 items are completed
12-07 15:37:56.696  4866  8983 I DownloadManager: Download 1181 finished with status SUCCESS
12-07 15:37:56.696  3463  4443 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3e1b90 u0 com.samsung.storyservice.eventUpgrade qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5268deb 8624:com.samsung.storyservice/5004}
12-07 15:37:56.696  8624  8624 I ServiceUtils: [StoryService] getSharedPrefLong retVal: 2 
12-07 15:37:56.696  8624  8624 I ServiceUtils: [StoryService] setSharedPrefLong : 2 
12-07 15:37:56.706  3463  3492 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{737cc89 u0 com.samsung.storyservice.eventUpgrade qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5268deb 8624:com.samsung.storyservice/5004}
12-07 15:37:56.706  8624  8624 I ServiceUtils: [StoryService] getSharedPrefLong retVal: 2 
12-07 15:37:56.706  8624  8624 I ServiceUtils: [StoryService] setSharedPrefLong : 2 
12-07 15:37:56.726  3463  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e0a048e u0 com.google.android.music.IMPORT_COMPLETE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8be16c 5399:com.google.android.music:main/u0a128}
12-07 15:37:56.726  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@6be33b4 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:56.736  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
12-07 15:37:56.736  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:56.746  3463  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9160bc u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ea494 8014:com.sec.android.daemonapp/u0a166}
12-07 15:37:56.746  8014  8014 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC05C1B1077ADBDFCD26E0DD65F89F33B4FE17DC1B474497D31FC899B742F59FC7E2530D44AA0E0C337CE79DB8742B2E258F6CB339704D31C42A8D7DC7C423413771689541177F15128C5082E60F137378548A4A3E3BC46E58400842019503B6A49C8E5B66CD635265353D3A3BD633961]}
12-07 15:37:56.746  5399  5399 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
12-07 15:37:56.746  8014  8014 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-07 15:37:56.746  8014  8014 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC94DE00B25794211F94C1928DF937E6B475EC9A5D52E6E8AB8C5E9065071E1EA]}
12-07 15:37:56.746  5399  9244 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
12-07 15:37:56.756  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
12-07 15:37:56.756  6182  6182 I CocktailBarUiController: onViewDataChanged : cocktailId = 9 viewId = 2131755213
12-07 15:37:56.756  3463  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9160bc u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ea494 8014:com.sec.android.daemonapp/u0a166}
12-07 15:37:56.756  8014  8014 D [WeatherWidget(1240)]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD1E8C40D052B00F217143F036334087D4E6A20622B7C5BAFDDAD05806F64279CFB58ACC644B946D1D44C1CB1343E9933E78640F20943B210E98A310C2B6492635456F7A98A5575530AC106B72D841268FE4ABD25C67426FA9138DA38B471E495644FE77123B7000FBE859923F0050324E]}
12-07 15:37:56.756  8014  8014 D [WeatherWidget(1240)]  : {[60E0DA3EB75B6AC8E852DC6D590E8782BC8A388398CF80A085FDDBC5F835D3B9]}
12-07 15:37:56.766  8014  8014 D [WeatherWidget(1240)]  : {[474171746BF601005A4D7D98B25C76B809703E254FE098232F11662B7CFA9306AAA83BB048A13628F045F41D951A5325AE3AF9B32C6D1DD1DC31B963A62AF276362FB0436AF461E46827C6999B8AF63FE3E53B8E7C650FB4537EBF1D6F8067C948D7C1C54AB097190AFAAEFD34E60697]}
12-07 15:37:56.776  3463  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9160bc u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ea494 8014:com.sec.android.daemonapp/u0a166}
12-07 15:37:56.776  8014  8014 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512D204533BF333E4D2CEAD653C68E1B222E4748640A665E8FB625C2496224988A01822F94E1D5511EDA528C1BE4CAEABD1D9C6A4F90F6430CF4A4F5AB6F2AF9127520AD0A30D99495D03E7BBCB8D48F747F2FF12B441DB9FDD66804D1185ECF265D727A94D84DA9FC743DD76C54F03F188]}
12-07 15:37:56.776  8014  8014 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-07 15:37:56.776  8014  8014 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B774749751274237807901AA8393F0A8526192EEF19F2D7E71ABBE368E57B1937778E7A2758BD22312FFA1C721753FCFDC0AD054D98]}
12-07 15:37:56.786  3463  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7a845 u0 com.android.mms.intent.action.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47287ef 5962:com.android.mms/u0a55}
12-07 15:37:56.796  3463  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca5db9a u0 android.intent.action.MEDIA_SCANNER_STARTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8be16c 5399:com.google.android.music:main/u0a128}
12-07 15:37:56.796  5399  5399 D MusicLifecycle: com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@6be33b4 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:56.806  5399  5399 D MusicLifecycle: com.google.android.music.store.MediaStoreImportService generated event: Service created
12-07 15:37:56.816  9246  9246 E Zygote  : v2
12-07 15:37:56.816  9246  9246 I libpersona: KNOX_SDCARD checking this for 10113
12-07 15:37:56.816  9246  9246 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-07 15:37:56.816  9246  9246 I libpersona: KNOX_SDCARD not a persona
12-07 15:37:56.816  3463  4062 I ActivityManager: Start proc 9246:com.google.android.gm/u0a113 for broadcast-3 com.google.android.gm/.widget.GmailWidgetProvider
12-07 15:37:56.816  9246  9246 E Zygote  : accessInfo : 0
12-07 15:37:56.816  9246  9246 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.gm 
12-07 15:37:56.826  5399  5399 D MusicLifecycle: com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
12-07 15:37:56.836  9246  9246 D TimaKeyStoreProvider: TimaSignature is unavailable
12-07 15:37:56.836  9246  9246 D ActivityThread: Added TimaKeyStore provider
12-07 15:37:56.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:37:56.846  3463  4339 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{571cca8 u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
12-07 15:37:56.846  9246  9246 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-07 15:37:56.846  9246  9246 D RelationGraph: garbageCollect()
12-07 15:37:56.846  9246  9246 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.google.android.gm rsrc of package com.google.android.gm
12-07 15:37:56.846  3463  4637 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-07 15:37:56.856  9246  9246 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-07 15:37:56.856  9246  9246 D ResourcesManager: For user 0 new overlays fetched Null
12-07 15:37:56.856  9246  9246 I InjectionManager: Inside getClassLibPath caller 
12-07 15:37:56.856  9246  9246 W System  : ClassLoader referenced unknown path: /system/app/Gmail2/lib/arm64
12-07 15:37:56.886  9246  9260 I Gmail   : getAccountsCursor
12-07 15:37:56.886  9246  9261 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
12-07 15:37:56.896  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:56.916  9246  9246 W Primes  : Primes.initialize(...) must be called before using any instrumentation, instrumentation will be skipped.
12-07 15:37:56.916  9246  9261 I Gmail   : Initiated Service map for: [gPop3, gLegacyImap, gEas, gmail]
12-07 15:37:56.916  9246  9246 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
12-07 15:37:56.926  3463  4339 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gm cmp = com.android.email.service.AttachmentService newState = 2 callingPackage = 10113
12-07 15:37:56.926  9246  9246 W Primes  : Primes.initialize(...) must be called before using any instrumentation, instrumentation will be skipped.
12-07 15:37:56.936  3463  3492 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } U=0: not found
12-07 15:37:56.936  9246  9246 D InjectionManager: InjectionManager
12-07 15:37:56.936  9246  9246 D InjectionManager: fillFeatureStoreMap com.google.android.gm
12-07 15:37:56.936  9246  9246 I InjectionManager: Constructor com.google.android.gm, Feature store :{}
12-07 15:37:56.936  9246  9246 I InjectionManager: featureStore :{}
12-07 15:37:56.946  9246  9270 I Gmail   : Observing account changes for notifications
12-07 15:37:56.946  3463  4990 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } U=0: not found
12-07 15:37:56.956  3463  4443 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71788c0 u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
12-07 15:37:56.966  3463  3857 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } U=0: not found
12-07 15:37:56.966  3463  4637 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gm cmp = com.android.email.service.EasAuthenticatorServiceAlternate newState = 2 callingPackage = 10113
12-07 15:37:56.966  9246  9271 I Gmail   : No Email application installed
12-07 15:37:56.966  9246  9271 I EmailMigration: No data to migrate
12-07 15:37:56.966  9246  9271 W EmailMigration: No Exchange migration, not the right Email provider version
12-07 15:37:56.976  9246  9273 I Gmail   : getAccountsCursor
12-07 15:37:56.976  3463  4413 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gm cmp = com.android.email.service.EasAuthenticatorService newState = 2 callingPackage = 10113
12-07 15:37:56.976  3463  4063 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e46ad3e u0 com.google.android.gm.intent.ACTION_PROVIDER_CREATED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
12-07 15:37:56.996  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:57.016  3463  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3394ebb u0 android.intent.action.MEDIA_SCANNER_FINISHED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{918c9a6 8564:com.samsung.cmh:CMH/5004}
12-07 15:37:57.016  8564  8564 E Controller: [#CMH#] FINISHED  EVENT_MEDIA_SCAN_FINISHED
12-07 15:37:57.016  8564  8564 I ControllerEventHandler: [#CMH#] onSystemRebooted 
12-07 15:37:57.016  8564  8564 I BaseThreadPoolExecutor: [#CMH#] Task com.samsung.cmh.database.DatabaseRebuilderTask@f7bf369 is submitted
12-07 15:37:57.016  8564  8620 I DatabaseRebuilderTask: [#CMH#] syncCMHDB started  
12-07 15:37:57.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:37:57.026  9239  9239 I FIPS_bssl: FIPS approved mode (1) | 9239 | app_process
12-07 15:37:57.026  9239  9239 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-07 15:37:57.036  8564  8564 I StorageController: [#CMH#] id: EVENT_MEDIA_SCAN_FINISHEDBundle = Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
12-07 15:37:57.036  9239  9239 D AndroidRuntime: CheckJNI is OFF
12-07 15:37:57.036  9239  9239 D AndroidRuntime: readGMSProperty: start
12-07 15:37:57.036  9239  9239 D AndroidRuntime: readGMSProperty: already setted!!
12-07 15:37:57.036  9239  9239 D AndroidRuntime: propertySet: couldn't set property (it is from app)
12-07 15:37:57.036  9239  9239 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
12-07 15:37:57.036  9239  9239 D AndroidRuntime: readGMSProperty: end
12-07 15:37:57.036  9239  9239 D AndroidRuntime: addProductProperty: start
12-07 15:37:57.036  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:57.036  3463  3493 I ActivityManager: Killing 8891:com.android.incallui/1001 (adj 15): DHA:empty #33
12-07 15:37:57.046  3463  3493 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3394ebb u0 android.intent.action.MEDIA_SCANNER_FINISHED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8be16c 5399:com.google.android.music:main/u0a128}
12-07 15:37:57.046  5399  5399 D MusicLifecycle: com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@6be33b4 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
12-07 15:37:57.056  9239  9239 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-07 15:37:57.066  9246  9276 I Gmail   : getAccountsCursor
12-07 15:37:57.066  5399  5399 D MusicLifecycle: com.google.android.music.store.MediaStoreImportService generated event: Service created
12-07 15:37:57.066  3463  3857 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e24369 u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
12-07 15:37:57.076  8564  8620 I DatabaseRebuilderTask: [#CMH#] No of Uris that are present in media :  0
12-07 15:37:57.076  8564  8620 I DatabaseRebuilderTask: [#CMH#] No of Uris that are present in CMH :  0
12-07 15:37:57.076  8564  8620 I DatabaseRebuilderTask: [#CMH#] No of Uris that are present in both Media and CMH:  0
12-07 15:37:57.076  8564  8620 I DatabaseRebuilderTask: [#CMH#] Insert =  0 Delete =  0
12-07 15:37:57.076  8564  8620 I DatabaseRebuilderTask: [#CMH#] syncCMHDB ended  0
12-07 15:37:57.076  3463  4989 D ActivityManager: isAutoRunBlockedApp:: com.android.incallui, Auto Run ON
12-07 15:37:57.086  9239  9239 I Radio-JNI: register_android_hardware_Radio DONE
12-07 15:37:57.086  9239  9239 E AffinityControl: AffinityControl: registerfunction enter
12-07 15:37:57.096  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-07 15:37:57.096  9239  9239 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-07 15:37:57.116  8564  8620 I DatabaseRebuilderTask: [#CMH#]  sending broadcast for Event title upgrade  
12-07 15:37:57.116  8564  8564 I CMHService: [#CMH#] onCreate() 
12-07 15:37:57.116  8564  9286 I Controller: [#CMH#] com.android.providers.media Insert
12-07 15:37:57.116  8564  9286 I Controller: [#CMH#] startSmartClustering starting clustering 
12-07 15:37:57.116  9101  9101 I IPService: [IPService] onStopService () called 
12-07 15:37:57.116  8564  9286 I Controller: [#CMH#] startSmartClustering starting day clustering 
12-07 15:37:57.116  8624  8624 I StoryService: [StoryService] onStopService() 
12-07 15:37:57.116  8564  9286 I Controller: [#CMH#] startDaywiseClustering starting day clustering 
12-07 15:37:57.116  9113  9113 I FaceService: [FaceService] onStopService() called 
12-07 15:37:57.116  8624  8624 I ServiceController: [StoryService] Sending response for  34 with status 35
12-07 15:37:57.126  3463  3493 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2575cab u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ea494 8014:com.sec.android.daemonapp/u0a166}
12-07 15:37:57.126  8564  8616 I ClusteringTask: [#CMH#] before mutex 
12-07 15:37:57.126  8564  8616 I ClusteringTask: [#CMH#] after mutex 
12-07 15:37:57.126  8564  8616 I MomentClusteringAlgo: [#CMH#] performClustering images deleted false
12-07 15:37:57.126  8564  8616 I ClusteringDBUtils: [#CMH#] updateClusterTable In nothing to update 
12-07 15:37:57.126  8564  8617 I DayClusteringTask: [#CMH#] before mutex 
12-07 15:37:57.126  8564  8617 I DayClusteringTask: [#CMH#] after mutex 
12-07 15:37:57.126  8564  8617 I DayClusteringTask: [#CMH#] internalRun Cluster size after image deletion:  0
12-07 15:37:57.126  8564  8617 I ClusteringDBUtils: [#CMH#] No clusters..!! 
12-07 15:37:57.126  8014  8014 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC05C1B1077ADBDFCD26E0DD65F89F33B4FE17DC1B474497D31FC899B742F59FC7E2530D44AA0E0C337CE79DB8742B2E258F6CB339704D31C42A8D7DC7C423413771689541177F15128C5082E60F137378548A4A3E3BC46E58400842019503B6A49C8E5B66CD635265353D3A3BD633961]}
12-07 15:37:57.126  8564  8615 I DayAndMonthTask: [#CMH#] before mutex 
12-07 15:37:57.126  8564  8615 I DayAndMonthTask: [#CMH#] after mutex 
12-07 15:37:57.126  8564  8615 I DayAndMonthTask: [#CMH#] after mutex release 
12-07 15:37:57.126  8564  8617 I TimeBasedClustering: [#CMH#] performClustering insertimages In 0 
12-07 15:37:57.126  8014  8014 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-07 15:37:57.126  8014  8014 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC94DE00B25794211F94C1928DF937E6B475EC9A5D52E6E8AB8C5E9065071E1EA]}
12-07 15:37:57.126  8564  8564 I CMHService: [#CMH#] onDestroy() 
12-07 15:37:57.136  8564  8617 I DayClusteringTask: [#CMH#] internalRun Cluster size after image insertion:  0
12-07 15:37:57.136  8564  8617 I ClusteringDBUtils: [#CMH#] No clusters..!! 
12-07 15:37:57.136  8564  8617 I DayClusteringTask: [#CMH#] startLocationClustering In  0
12-07 15:37:57.136  8564  8617 I DayClusteringTask: [#CMH#] internalRun::No more Images/Videos to process, Finished Task, Exiting  
12-07 15:37:57.136  8564  8617 I DayClusteringTask: [#CMH#] after mutex release 
12-07 15:37:57.136  8564  8620 I BaseThreadPoolExecutor: [#CMH#] afterExecute FutureTask
12-07 15:37:57.136  8564  8616 I MomentClusteringAlgo: [#CMH#] performClustering In 0 
12-07 15:37:57.136  8564  8616 I ClusteringTask: [#CMH#] Cluster size: 0
12-07 15:37:57.136  8564  8616 I ClusteringDBUtils: [#CMH#] updateClusterTable In nothing to update 
12-07 15:37:57.136  8564  8616 I ClusteringTask: [#CMH#] after mutex release 
12-07 15:37:57.136  9239  9239 D AndroidRuntime: Shutting down VM
12-07 15:37:57.156  3463  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2575cab u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ea494 8014:com.sec.android.daemonapp/u0a166}
12-07 15:37:57.156  8014  8014 D [WeatherWidget(1240)]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD1E8C40D052B00F217143F036334087D4E6A20622B7C5BAFDDAD05806F64279CFB58ACC644B946D1D44C1CB1343E9933E78640F20943B210E98A310C2B6492635456F7A98A5575530AC106B72D841268FE4ABD25C67426FA9138DA38B471E495644FE77123B7000FBE859923F0050324E]}
12-07 15:37:57.156  8014  8014 D [WeatherWidget(1240)]  : {[60E0DA3EB75B6AC8E852DC6D590E8782BC8A388398CF80A085FDDBC5F835D3B9]}
12-07 15:37:57.156  8014  8014 D [WeatherWidget(1240)]  : {[474171746BF601005A4D7D98B25C76B809703E254FE098232F11662B7CFA9306AAA83BB048A13628F045F41D951A5325AE3AF9B32C6D1DD1DC31B963A62AF276362FB0436AF461E46827C6999B8AF63FE3E53B8E7C650FB4537EBF1D6F8067C948D7C1C54AB097190AFAAEFD34E60697]}
12-07 15:37:57.176  3463  4062 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2575cab u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f6ea494 8014:com.sec.android.daemonapp/u0a166}
12-07 15:37:57.176  8014  8014 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512D204533BF333E4D2CEAD653C68E1B222E4748640A665E8FB625C2496224988A01822F94E1D5511EDA528C1BE4CAEABD1D9C6A4F90F6430CF4A4F5AB6F2AF9127520AD0A30D99495D03E7BBCB8D48F747F2FF12B441DB9FDD66804D1185ECF265D727A94D84DA9FC743DD76C54F03F188]}
12-07 15:37:57.176  8014  8014 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-07 15:37:57.176  8014  8014 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B774749751274237807901AA8393F0A8526192EEF19F2D7E71ABBE368E57B1937778E7A2758BD22312FFA1C721753FCFDC0AD054D98]}
12-07 15:37:57.186  3463  4062 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b0bf08 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
12-07 15:37:57.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:37:57.216  3463  4431 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a5f6a1 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
12-07 15:37:57.226  3463  4443 V AlarmManager:  remove PendingIntent] PendingIntent{65540c6: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
12-07 15:37:57.246  5399  9277 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
12-07 15:37:57.256  5399  5399 D MusicLifecycle: com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
12-07 15:37:57.276  3463  4989 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2d1887 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
12-07 15:37:57.286  3463  3493 V AlarmManager:  remove PendingIntent] PendingIntent{f16c3b4: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
12-07 15:37:57.326  3463  4326 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8a5bdd u0 com.android.providers.calendar.intent.CalendarProvider2 qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6b6668d 8125:com.android.providers.calendar/u0a50}
12-07 15:37:57.326  3463  4432 V AlarmManager:  remove PendingIntent] PendingIntent{8b8b623: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
12-07 15:37:57.346  3463  4413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{366720 u0 com.samsung.storyservice.eventUpgrade qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5268deb 8624:com.samsung.storyservice/5004}
12-07 15:37:57.346  8624  8624 I ServiceUtils: [StoryService] getSharedPrefLong retVal: 2 
12-07 15:37:57.346  8624  8624 I ServiceUtils: [StoryService] setSharedPrefLong : 2 
,12-07 15:37:57.356  3463  4413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d55d8d9 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12d6d73 5053:com.samsung.android.providers.context/u0a9}
,12-07 15:37:57.376  3463  4413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{675a29e u0 com.samsung.android.providers.context.log.action.USE_MULTI_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12d6d73 5053:com.samsung.android.providers.context/u0a9}
,12-07 15:37:57.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:57.376  3463  3582 D PowerManagerService: [s] UserActivityState : 1 -> 2
,12-07 15:37:57.386  3463  4413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd6917f u0 android.intent.action.DOWNLOAD_COMPLETE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb312d3 4577:com.google.android.gms/u0a21}
,12-07 15:37:57.386  4577  4577 I Vision  : Supported ABIS: [arm64-v8a, armeabi-v7a, armeabi]
,12-07 15:37:57.406  3463  4443 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd6917f u0 android.intent.action.DOWNLOAD_COMPLETE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
,12-07 15:37:57.416  4327  4327 I ConfigService: onCreate
,12-07 15:37:57.426  3463  4990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd6917f u0 android.intent.action.DOWNLOAD_COMPLETE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb312d3 4577:com.google.android.gms/u0a21}
,12-07 15:37:57.446  3463  4063 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{768ca11 u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
,12-07 15:37:57.446  4327  6458 E WorkSourceUtil: Could not find package: com.google.android.gms.vision
,12-07 15:37:57.466  3463  3493 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8273177 u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
,12-07 15:37:57.486  3463  3493 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{afef64d u0 com.google.android.gm.intent.ACTION_PROVIDER_CREATED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
,12-07 15:37:57.506  3463  4431 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d536e13 u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
,12-07 15:37:57.536  3463  4063 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{951aa49 u0 com.samsung.storyservice.eventUpgrade qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5268deb 8624:com.samsung.storyservice/5004}
,12-07 15:37:57.536  8624  8624 I ServiceUtils: [StoryService] getSharedPrefLong retVal: 2 
12-07 15:37:57.536  8624  8624 I ServiceUtils: [StoryService] setSharedPrefLong : 2 
,12-07 15:37:57.546  3463  4990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71def4e u0 com.google.android.music.IMPORT_COMPLETE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8be16c 5399:com.google.android.music:main/u0a128}
,12-07 15:37:57.546  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@6be33b4 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,12-07 15:37:57.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:57.556  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,12-07 15:37:57.556  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,12-07 15:37:57.566  5399  5399 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,12-07 15:37:57.566  5399  9300 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,12-07 15:37:57.566  3463  4990 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c74297c u0 com.android.mail.ACTION_NOTIFY_DATASET_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbf83c1 9246:com.google.android.gm/u0a113}
,12-07 15:37:57.576  5399  5399 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,12-07 15:37:57.596  3463  4063 D WifiService: startScan by pid=4577, uid=10021
,12-07 15:37:57.606  3463  3863 I WifiScanController: location is disabled
,12-07 15:37:57.606  3463  3863 D WifiStateMachine: CMD_START_SCAN : scanLog.mLast - 1481121477609, scanLog.mStartTimeForBigdata - 1481121477609
,12-07 15:37:57.616  4128  4128 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
12-07 15:37:57.616  4128  4128 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-07 15:37:57.626  4128  4128 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,12-07 15:37:57.636  4577  9295 W DownloadCompleteService: SHA-1 of downloaded file does not match request
,12-07 15:37:57.666  3463  4062 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,12-07 15:37:57.666  4866  9303 I DownloadManager: [1181] create new because it's not in HashMap.
,12-07 15:37:57.666  4866  9303 V DownloadManager: 1 items are Removed
,12-07 15:37:57.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:57.826  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:37:57.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:58.076  3463  4257 D SLocation: handleBootCompleted
,12-07 15:37:58.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:58.256  3463  3974 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.checkin.CheckinService newState = 2 callingPackage = 10021
,12-07 15:37:58.276  3463  4637 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.update.SystemUpdateActivity newState = 2 callingPackage = 10021
,12-07 15:37:58.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:58.286  3463  4062 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver newState = 2 callingPackage = 10021
,12-07 15:37:58.306  3463  3493 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.update.SystemUpdateService$Receiver newState = 2 callingPackage = 10021
,12-07 15:37:58.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:58.526  3154  3637 D Netd    : Iface wlan0 link up
,12-07 15:37:58.536  4128  4128 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
,12-07 15:37:58.536  5067  5078 D PdnController: Interface Changed wlan0 link up
12-07 15:37:58.536  3463  3563 D Tethering: interfaceLinkStateChanged wlan0, true
12-07 15:37:58.536  3463  3563 D Tethering: interfaceStatusChanged wlan0, true
,12-07 15:37:58.546  3463  3861 D WifiP2pService: InactiveState{ what=147461 }
12-07 15:37:58.546  3463  3861 D WifiP2pService: P2pEnabledState{ what=147461 }
,12-07 15:37:58.546  3463  3861 D WifiP2pService: DefaultState{ what=147461 }
,12-07 15:37:58.596  3463  3463 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-07 15:37:58.606  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1116667 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fd511f 3952:com.android.systemui/u0a65}
,12-07 15:37:58.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:58.636  3463  3560 I ActivityManager: Waited long enough for: ServiceRecord{ab51821 u0 com.trustonic.tuiservice/.TuiService}
,12-07 15:37:58.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:58.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:59.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:59.216  3463  3857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:37:59.226  3463  3857 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:37:59.226  3463  3857 D BatteryService: online:4, current avg:-707, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:207
12-07 15:37:59.226  3463  3857 D BatteryService: stay LED for charging
12-07 15:37:59.226  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:37:59.226  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:37:59.226  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:37:59.226  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:37:59.226  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:37:59.236  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:37:59.236  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:37:59.236  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
12-07 15:37:59.236  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:37:59.246  3952  3952 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-07 15:37:59.246  3952  3952 D PowerUI.Notification: There is no change about charging status, so return!
,12-07 15:37:59.256  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:37:59.266  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:37:59.266  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:37:59.276  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:37:59.276  4719  4719 D BatteryController: saveBatteryData : level[100], status[2]
,12-07 15:37:59.286  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-07 15:37:59.286  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:37:59.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:59.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:59.676  3463  4152 E Watchdog: !@Sync 1 [12-07 15:37:59.679]
,12-07 15:37:59.686  3463  6435 D SSRM:n  : SIOP:: AP = 460, PST = 475 (W:4), CP = 319, CUR = -707, LCD = 1
,12-07 15:37:59.716  3463  6435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-07 15:37:59.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:59.776  3463  3879 D SettingsProvider: isChangeAllowed() : name = audio_safe_volume_state
,12-07 15:37:59.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:37:59.996  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:38:00.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:00.136  8564  8586 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,12-07 15:38:00.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:00.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:00.566  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:38:00.566  3463  3820 V AlarmManager: Send whitelist package alarm :PendingIntent{2a49b9f: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:38:00.576  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-07 15:38:00.576  3952  3952 D KeyguardUpdateMonitor: handleTimeUpdate
,12-07 15:38:00.596  3952  3952 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-07 15:38:00.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:00.676  3952  3952 D DateView: received broadcast android.intent.action.TIME_TICK
,12-07 15:38:00.706  8014  8014 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-07 15:38:00.716  8014  8014 W [WeatherWidget(1240)]  : {[15CF912BDCF42F9CFB4A85BDA543B9C03270F5FAA9F5676E82AF8C619BCF91CE5FB3CE2082F25CD9A43F9287628E184E1B535DD573D2968B1284E288CF459C13DF414A1402CD333D136FA7792C603AC4]}
,12-07 15:38:00.716  8014  8014 D [WeatherWidget(1240)]  AutoRefresh: {[9BDBD671986BB5350BB30F5195E2700D025AD0AB6B43765153FE15B38684E558D03F28FB0B91AB39310ABEC4D7D82D6E635843040DF4C0F1B9C2397CFFDE153E031020FC4E2C26F3A31388ED7A346963]}
,12-07 15:38:00.716  8014  8014 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-07 15:38:00.716  8014  8014 D [WeatherWidget(1240)]  : {[9F9F443422C90E3D1C251B879888811D9BE8F5469D72520331506A4B883A4D63F11DD6D802FFA8F6CE10F27B8D429FC5]}
,12-07 15:38:00.716  8014  8014 D [WeatherWidget(1240)]  : {[68086835334BD11DCD92A5E633AE22E2D31F6EB793B927E1EFC2545E08F3928E96ECD7F469DC78A2FA30FE5745C0F4C5]}
,12-07 15:38:00.726  8014  8014 D [WeatherWidget(1240)]  : {[00E3D6BBB5F57518CE2AE63D1C0379D98B2214ED769C08BFA216B2BA55E91A620DC80E9633ECD3EFD4D65A30244FC1F0]}
,12-07 15:38:00.736  4719  4719 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-07 15:38:00.736  4719  4719 V BatteryController: getBatteryLevel[100.0], batteryStatus[2]
,12-07 15:38:00.736  3463  4431 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:38:00.736  3463  4431 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,12-07 15:38:00.736  3463  4431 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-07 15:38:00.736  3463  4431 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,12-07 15:38:00.736  3169  7762 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-07 15:38:00.746  3463  4431 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-07 15:38:00.746  3463  4431 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-07 15:38:00.746  3463  4431 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-07 15:38:00.746  4719  4719 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e89b19, service=Device Physical Context Monitor
,12-07 15:38:00.746  4719  4719 I AlpmModeManager: startAlpmMode : state  = BLANK
,12-07 15:38:00.756  4719  4719 D DefaultClockView: Window showed. Time views updating
,12-07 15:38:00.756  3463  4637 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:38:00.756  3463  4637 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:00.756  3463  4637 D PowerManagerService: mDisplayReady: false
,12-07 15:38:00.756  3463  4637 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:38:00.756  3463  4637 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:00.756  4719  4719 D AODUpdatePositionController: updatePosition: direction[1] updatePosition: X[-3] Y[396] NewPositionTimer[59]
12-07 15:38:00.756  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-07 15:38:00.756  4719  4719 D DefaultClockView: LocalTime Pattern : HH:mm
12-07 15:38:00.756  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:00.756  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:38:00.756  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:00.756  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-07 15:38:00.756  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:00.756  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:38:00.756  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:38:00.756  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:38:00.766  4719  4719 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 15:38 time02: null ampm: null
,12-07 15:38:00.776  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:00.776  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:00.776  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:00.776  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:00.776  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:00.776  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:00.776  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:00.776  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:00.776  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:00.776  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:00.776  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:00.776  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:00.776  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:00.786  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:38:00.786  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:00.786  4719  4719 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-07 15:38:00.786  4719  4719 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-07 15:38:00.796  4719  4719 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:śr., 7 gru 15:38
,12-07 15:38:00.796  4719  4719 I AODService.ClockTimer: startAlarm : TICK
,12-07 15:38:00.796  3463  4339 V AlarmManager: Add whitelist package alarm :PendingIntent{2c40203: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:38:00.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:00.796  4719  4719 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-07 15:38:00.796  4719  4719 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-07 15:38:00.796  3463  4326 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-07 15:38:00.796  3463  4326 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-07 15:38:00.796  3463  4063 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:38:00.806  3169  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-07 15:38:00.806  3463  3823 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
12-07 15:38:00.806  3463  3822 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 38, 0,
12-07 15:38:00.806  3463  3822 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 38, 0
12-07 15:38:00.806  3169  3169 D Sensorhubs: sendContextData: -63, 14, 14, 38, 0
12-07 15:38:00.806  4719  4719 D DefaultClockView: RootView invalidate()
12-07 15:38:00.806  3463  4058 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:38:00.806  3463  3822 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-07 15:38:00.806  3463  3822 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-07 15:38:00.806  3463  3822 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-07 15:38:00.816  3463  3822 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,12-07 15:38:00.816  3463  3822 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
12-07 15:38:00.816  3463  3825 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-07 15:38:00.836  4719  4719 I AODService: onSContextChanged: AODScreenShown state is already true
,12-07 15:38:00.956  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
,12-07 15:38:00.956  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:00.956  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:38:00.956  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:38:00.956  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:38:00.956  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:00.956  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:00.956  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
,12-07 15:38:00.956  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:00.956  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:38:00.956  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:00.956  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-07 15:38:00.956  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:38:00.956  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:38:00.976  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:00.976  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:00.976  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:00.976  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:00.976  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:00.976  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:00.976  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:38:00.976  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:00.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:38:00.976  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:00.976  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:00.976  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-07 15:38:00.976  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:00.976  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:00.996  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:38:00.996  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:01.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:01.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:01.466  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:38:01.486  3463  3560 I ActivityManager: Waited long enough for: ServiceRecord{4860c45 u0 com.samsung.fresco.logging/.FrescoService}
,12-07 15:38:01.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:01.566  8650  8650 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=3 stopped=true)
,12-07 15:38:01.576  3463  4989 I ActivityManager: Killing 8678:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #33
,12-07 15:38:01.606  3463  3857 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,12-07 15:38:01.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:01.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:01.976  9246  9266 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,12-07 15:38:01.996  4577  4577 I GAv4-SVC: Google Analytics 8.7.05 is starting up.
,12-07 15:38:02.026  3463  4432 V AlarmManager:  remove PendingIntent] PendingIntent{87abb5f: PendingIntentRecord{613e4f4 com.google.android.gms broadcastIntent}}
,12-07 15:38:02.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:02.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:02.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:02.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:02.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:02.826  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:02.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:02.966  4327  4327 I ConfigService: onDestroy
,12-07 15:38:03.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:03.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:03.376  3463  3582 D PowerManagerService: [s] UserActivityState : 2 -> 4
,12-07 15:38:03.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:03.536  3463  3560 I ActivityManager: Waited long enough for: ServiceRecord{545e789 u0 com.sec.spp.push/.PushClientService}
,12-07 15:38:03.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:03.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:04.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:04.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:04.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:04.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:04.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:04.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:05.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:05.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:05.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:05.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:05.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:06.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:06.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:06.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:06.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:06.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:06.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:07.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:07.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:07.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:07.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:07.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:07.826  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:07.866  8650  8666 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,12-07 15:38:07.876  8650  8668 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,12-07 15:38:07.886  3463  4989 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
,12-07 15:38:07.936  3463  4058 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,12-07 15:38:07.956  8650  8650 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,12-07 15:38:07.956  8650  8650 W Babel   : BAM#gBA: invalid account id: -1
12-07 15:38:07.956  8650  8650 W Babel   : BAM#gBA: invalid account id: -1
12-07 15:38:07.956  8650  8650 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,12-07 15:38:07.956  8650  8675 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,12-07 15:38:07.976  3463  4062 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,12-07 15:38:07.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:08.106  4167  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=10436,extra=Bundle[mParcelledData.dataSize=84]
12-07 15:38:08.106  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
,12-07 15:38:08.106  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
12-07 15:38:08.106  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-07 15:38:08.106  4167  4167 I PeopleDataManager: removeNotification
12-07 15:38:08.106  4167  4167 I NotificationParser: getNotiType:com.google.android.talk,null
12-07 15:38:08.106  4167  4167 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
12-07 15:38:08.106  4167  4167 D PeopleDataManager: removeNotiInfo =null
,12-07 15:38:08.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:08.316  3463  3493 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.update.SystemUpdateService newState = 2 callingPackage = 10021
,12-07 15:38:08.326  3463  4062 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.checkin.EventLogService newState = 2 callingPackage = 10021
,12-07 15:38:08.346  3463  4063 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gsf cmp = com.google.android.gsf.checkin.EventLogService$Receiver newState = 2 callingPackage = 10021
,12-07 15:38:08.356  4577  7768 I CheckinService: Done disabling old GoogleServicesFramework version
12-07 15:38:08.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:08.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:08.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:08.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:09.056  3463  3560 I ActivityManager: Waited long enough for: ServiceRecord{af2faa u0 com.sec.android.daemonapp/.appservice.WeatherService}
,12-07 15:38:09.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:09.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:09.266  3463  4990 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:38:09.276  3463  4990 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:38:09.276  3463  4990 D BatteryService: online:4, current avg:-168, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:215
,12-07 15:38:09.276  3463  4990 D BatteryService: stay LED for charging
12-07 15:38:09.276  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:38:09.276  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:38:09.276  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:38:09.276  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:38:09.276  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:38:09.286  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:38:09.286  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:38:09.286  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
12-07 15:38:09.286  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:38:09.296  3952  3952 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-07 15:38:09.296  3952  3952 D PowerUI.Notification: There is no change about charging status, so return!
,12-07 15:38:09.306  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:38:09.316  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:38:09.316  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:38:09.326  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:38:09.326  4719  4719 D BatteryController: saveBatteryData : level[100], status[2]
,12-07 15:38:09.346  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:09.346  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:09.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:09.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:09.746  3463  6435 D SSRM:n  : SIOP:: AP = 370, PST = 454 (W:5), CP = 305, CUR = -168, LCD = 1
,12-07 15:38:09.746  3463  6435 D N       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,12-07 15:38:09.756  4866  4866 D ContentApp:  LEVEL : 0
,12-07 15:38:09.756  8564  8583 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-07 15:38:09.756  8564  8583 I PolicyManager: [#CMH#] onReceive action = EVENT_SIOP
12-07 15:38:09.756  8564  8583 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-07 15:38:09.776  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35af498 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a60a1d9 8820:com.samsung.android.scloud:contentsync/5009}
,12-07 15:38:09.776  8820  8820 I [SC]DetectorReceiver: onReceive [android.intent.action.CHECK_SIOP_LEVEL]
,12-07 15:38:09.776  8820  8820 I [SC]CloudManager: requestInit
,12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : cachecreate fail, try again.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : cache create fail.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : thumbnailcreate fail, try again.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : thumbnail create fail.
,12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : sharecreate fail, try again.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : share create fail.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : scratchcreate fail, try again.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : scratch create fail.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : eventSynccreate fail, try again.
12-07 15:38:09.786  8820  8820 I [SC]Utils: folder : eventSync create fail.
,12-07 15:38:09.796  3463  6435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-07 15:38:09.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:09.806  8834  8845 I SA      : [SCU] isHaveSA() - false
12-07 15:38:09.806  8834  8845 I SA      : [OCP] Samsung account is not Signed-in
,12-07 15:38:09.806  8834  8845 I SA      : [OCP] Delete DB (TNC data)
,12-07 15:38:09.816  8820  8820 I [SC]CommonUtil: Samsung Account Not Logged in
,12-07 15:38:09.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:10.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:10.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:10.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:10.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:10.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:11.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:11.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:11.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:11.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:11.606  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:38:11.676  3463  3463 I BackgroundCompactionService: onStart. jobID=801
,12-07 15:38:11.676  3463  3463 I BackgroundCompactionService: onStart done. jobID=801
,12-07 15:38:11.676  3463  9323 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,12-07 15:38:11.676  3463  9323 I BackgroundCompactionService: compact_memory command done
,12-07 15:38:11.686  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:38:11.756  8564  8587 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,12-07 15:38:11.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:11.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:12.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:12.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:12.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:12.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:12.836  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:12.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:13.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:13.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:13.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:13.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:13.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:13.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:14.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:14.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:14.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:14.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:14.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:15.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:15.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:15.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:15.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:15.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:15.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:16.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:16.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:16.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:16.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:16.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:16.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:17.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:17.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:17.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:17.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:17.836  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:17.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:18.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:18.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:18.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:18.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:18.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:18.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:19.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:19.326  3463  4063 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:38:19.326  3463  4063 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:38:19.326  3463  4063 D BatteryService: online:4, current avg:62, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:235
12-07 15:38:19.326  3463  4063 D BatteryService: stay LED for charging
,12-07 15:38:19.326  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:38:19.336  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:38:19.336  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:38:19.336  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:38:19.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:38:19.336  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:38:19.336  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:38:19.336  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:38:19.346  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:38:19.346  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:38:19.346  3952  3952 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-07 15:38:19.346  3952  3952 D PowerUI.Notification: There is no change about charging status, so return!
,12-07 15:38:19.366  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:38:19.366  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:38:19.366  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:38:19.376  4719  4719 D BatteryController: saveBatteryData : level[100], status[2]
,12-07 15:38:19.376  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:38:19.396  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:19.396  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:19.516  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:38:19.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:19.526  3463  4989 V AlarmManager:  remove PendingIntent] PendingIntent{76f3a4f: PendingIntentRecord{b81f22c com.google.android.gms broadcastIntent}}
,12-07 15:38:19.526  3463  3860 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
12-07 15:38:19.526  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
12-07 15:38:19.526  3463  3860 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,12-07 15:38:19.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:19.816  3463  6435 D SSRM:n  : SIOP:: AP = 340, PST = 435 (W:6), CP = 289, CUR = 62, LCD = 1
,12-07 15:38:19.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:20.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:20.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:20.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:20.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:20.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:20.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:21.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:21.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:21.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:21.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:21.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:22.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:22.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:22.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:22.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:22.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:22.836  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:22.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:23.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:23.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:23.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:23.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:23.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:24.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:24.086  4577  9328 W IcingInternalCorpora: getNumBytesRead when not calculated.
,12-07 15:38:24.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:24.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:24.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:24.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:24.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:25.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:25.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:25.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:25.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:25.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:25.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:26.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:26.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:26.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:26.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:26.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:27.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:27.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:27.346  4167  4175 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.music,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,12-07 15:38:27.346  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.music}]
12-07 15:38:27.346  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
12-07 15:38:27.346  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-07 15:38:27.346  4167  4167 I PeopleDataManager: removeNotification
12-07 15:38:27.346  4167  4167 I NotificationParser: getNotiType:com.google.android.music,null
12-07 15:38:27.346  4167  4167 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.music,isEdgeNotification=false,key=null,removeAll=false
12-07 15:38:27.346  4167  4167 D PeopleDataManager: removeNotiInfo =null
,12-07 15:38:27.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:27.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:27.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:27.836  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:27.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:28.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:28.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:28.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:28.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:28.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:28.986  3952  3952 V KeyguardUpdateMonitor: onSubscriptionInfoChanged()
,12-07 15:38:28.996  3952  3952 V KeyguardUpdateMonitor: onSubscriptionInfoChanged: list is null
,12-07 15:38:29.006  3952  3952 D KeyguardCarrierText: onRefreshCarrierInfo: 
12-07 15:38:29.006  3952  3952 D KeyguardCarrierText: updateAllSlot
12-07 15:38:29.006  3952  3952 D KeyguardCarrierText: updateIntentData(): isMultiSIMState: falsesubId: 2147483643 phoneId:0plmn: Brak sieciSPN: 
12-07 15:38:29.016  3463  3857 D SecContentProvider2: query(), uri = 15 selection = getLockScreenHiddenItems
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: updateCarrierText(): isMultiSIMState: false
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: updateDate All slot
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: mSimState[0]ABSENT
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: mSimState[1]ABSENT
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: Getting plmn/spn sticky brdcst  mPlmn:Brak sieci / mSpn:  phoneId:0 subId:2147483643 showPlmn: true showSpn:false
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: getStatusForIccState :  SIM state = ABSENT
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: getCarrierTextForSimState :  SIM state = SimMissingcarrierText: Brak karty SIM | Brak sieci
12-07 15:38:29.026  3952  3952 D KeyguardCarrierText: Handling ABSENT , carrierTextForSimState = Brak karty SIM | Brak sieci
12-07 15:38:29.036  3952  3952 D KeyguardCarrierText: updateCarrierText insertedMultiSim = false
12-07 15:38:29.036  3952  3952 D KeyguardCarrierText: updateCarrierText State: Absent SIM Number = 0
,12-07 15:38:29.046  3952  3952 D KeyguardCarrierText: Getting plmn/spn sticky brdcst for Absent case Brak sieci/showPlmn: trueshowSpn: false phoneId:0 subId:2147483643
,12-07 15:38:29.046  3952  3952 D KeyguardCarrierText: concatenate : plmn = Brak sieci
12-07 15:38:29.046  3952  3952 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
12-07 15:38:29.046  3952  3952 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
12-07 15:38:29.046  3952  3952 D KeyguardCarrierText: setText :  displayText = Tryb Offline
,12-07 15:38:29.046  3952  3952 D EmergencyButton: onRefreshCarrierInfo
,12-07 15:38:29.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:29.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:29.376  3463  4989 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:38:29.376  3463  4989 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:38:29.376  3463  4989 D BatteryService: online:4, current avg:137, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:196
12-07 15:38:29.376  3463  4989 D BatteryService: stay LED for charging
,12-07 15:38:29.376  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:38:29.386  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:38:29.386  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:38:29.386  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:38:29.386  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:38:29.396  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:38:29.396  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:38:29.396  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:38:29.396  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:38:29.396  3952  3952 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-07 15:38:29.396  3952  3952 D PowerUI.Notification: There is no change about charging status, so return!
,12-07 15:38:29.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:29.416  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:38:29.416  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:38:29.426  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:38:29.426  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:38:29.426  4719  4719 D BatteryController: saveBatteryData : level[100], status[2]
,12-07 15:38:29.446  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-07 15:38:29.446  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:29.536  3463  3860 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,12-07 15:38:29.536  3463  3860 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,12-07 15:38:29.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:29.676  3463  4152 E Watchdog: !@Sync 2 [12-07 15:38:29.681]
,12-07 15:38:29.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:29.846  3463  6435 D SSRM:n  : SIOP:: AP = 320, PST = 418 (W:7), CP = 278, CUR = 137, LCD = 1
,12-07 15:38:29.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:30.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:30.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:30.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:30.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:30.816  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-07 15:38:30.816  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-07 15:38:30.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:31.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:31.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:31.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:31.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:31.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:31.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:32.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:32.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:32.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:32.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:32.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:32.836  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:33.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:33.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:33.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:33.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:33.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:33.736  3463  5104 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,12-07 15:38:33.736  3463  5104 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
12-07 15:38:33.736  3463  5104 V MARsPolicyManager: updateSMDBValues
,12-07 15:38:33.746  3463  3575 E MARsDBManager: updateDBAll : begin --size 0
12-07 15:38:33.746  3463  3575 E MARsDBManager: updateDBAll : end
,12-07 15:38:33.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:34.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:34.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:34.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:34.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:34.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:34.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:35.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:35.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:35.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:35.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:35.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:36.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:36.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:36.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:36.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:36.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:36.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:37.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:37.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:37.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:37.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:37.766  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:38:37.836  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:37.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:38.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:38.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:38.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:38.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:38.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:38.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:39.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:39.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:39.436  3463  4058 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:38:39.436  3463  4058 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4353, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:38:39.436  3463  4058 D BatteryService: online:4, current avg:185, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:237
12-07 15:38:39.436  3463  4058 D BatteryService: stay LED for charging
,12-07 15:38:39.436  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:38:39.446  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:38:39.446  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:38:39.446  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:38:39.446  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:38:39.446  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:38:39.446  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:38:39.456  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:38:39.456  3952  3952 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-07 15:38:39.456  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:38:39.456  3952  3952 D PowerUI.Notification: There is no change about charging status, so return!
,12-07 15:38:39.466  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:38:39.476  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:38:39.476  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:38:39.486  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:38:39.486  4719  4719 D BatteryController: saveBatteryData : level[100], status[2]
,12-07 15:38:39.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:39.506  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:39.506  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:39.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:39.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:39.876  3463  6435 D SSRM:n  : SIOP:: AP = 310, PST = 405 (W:8), CP = 272, CUR = 185, LCD = 1
,12-07 15:38:40.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:40.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:40.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:40.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:40.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:40.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:41.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:41.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:41.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:41.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:41.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:42.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:42.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:42.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:42.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:42.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:42.846  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:42.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:43.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:43.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:43.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:43.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:43.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:43.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:44.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:44.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:44.466  6518  6518 D FactoryTest: User mode
,12-07 15:38:44.466  6518  6518 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,12-07 15:38:44.466  6518  6518 D MTPRx   : still no open session command from host, so toast
,12-07 15:38:44.486  3463  4062 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,12-07 15:38:44.486  3463  4062 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,12-07 15:38:44.496  3463  4062 D ResourcesManager: For user 0 new overlays fetched Null
,12-07 15:38:44.496  3463  4062 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-07 15:38:44.496  3463  4062 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
,12-07 15:38:44.506  3463  4062 D ActivityManager: mDVFSHelper.acquire()
,12-07 15:38:44.516  3463  4062 V WindowManager: addAppToken: AppWindowToken{d035e1d5e token=Token{27c8699 ActivityRecord{9b833e0 u0 com.samsung.android.MtpApplication/.USBConnection t20}}} to stack=2 task=20 at 0
,12-07 15:38:44.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:44.546  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:38:44.546  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:44.556  3463  4062 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,12-07 15:38:44.576  3463  3463 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,12-07 15:38:44.576  6182  6193 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,12-07 15:38:44.596  6182  6192 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,12-07 15:38:44.606  3463  4062 D InputDispatcher: Focused application set to: xxxx
,12-07 15:38:44.606  6518  6518 E MTPRx   : started activity for popup
12-07 15:38:44.606  3463  3560 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
12-07 15:38:44.606  6518  6518 D RelationGraph: garbageCollect()
12-07 15:38:44.606  3463  3560 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
12-07 15:38:44.606  6518  6518 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
12-07 15:38:44.616  3463  6435 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
12-07 15:38:44.616  3463  6435 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-07 15:38:44.616  6518  6518 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
,12-07 15:38:44.626  3463  6435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-07 15:38:44.636  3463  6435 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
12-07 15:38:44.636  3463  6435 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-07 15:38:44.636  6518  6518 D MTPUSBConnection: onCreate in USBConnection
12-07 15:38:44.636  6518  6518 V MTPUSBConnection: Registering broadcast receiver.
,12-07 15:38:44.646  6518  6518 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,12-07 15:38:44.646  3463  4063 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,12-07 15:38:44.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:44.736  6518  6518 D TAG     : dev.kiessupport is : TRUE
,12-07 15:38:44.756  6518  6518 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-07 15:38:44.756  6518  6518 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a484f2d V.E...... R.....I. 0,0-0,0}
,12-07 15:38:44.756  3463  4990 W WindowManager: Failed looking up window
12-07 15:38:44.756  3463  4990 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@17f6fd1 does not exist
12-07 15:38:44.756  3463  4990 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14805)
12-07 15:38:44.756  3463  4990 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
12-07 15:38:44.756  3463  4990 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
12-07 15:38:44.756  3463  4990 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
12-07 15:38:44.756  3463  4990 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
12-07 15:38:44.756  3463  4990 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,12-07 15:38:44.756  3463  3974 D ISSUE_DEBUG: InputChannelName : 3fa7a36 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,12-07 15:38:44.766  6518  6518 D Activity: performCreate Call Injection manager
,12-07 15:38:44.766  6518  6518 I InjectionManager: dispatchOnViewCreated > Target : com.samsung.android.MtpApplication.USBConnection isFragment :false
,12-07 15:38:44.776  6518  6518 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{71385dc I.E...... R.....I. 0,0-0,0}
,12-07 15:38:44.776  3463  3857 W WindowManager: Failed looking up window
12-07 15:38:44.776  3463  3857 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@ea6ad37 does not exist
12-07 15:38:44.776  3463  3857 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14805)
12-07 15:38:44.776  3463  3857 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
12-07 15:38:44.776  3463  3857 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
12-07 15:38:44.776  3463  3857 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
12-07 15:38:44.776  3463  3857 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
12-07 15:38:44.776  3463  3857 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,12-07 15:38:44.776  3463  4339 D ISSUE_DEBUG: InputChannelName : 548b2a4 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,12-07 15:38:44.786  3463  4989 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,12-07 15:38:44.786  3463  4989 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
12-07 15:38:44.786  3463  3463 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-07 15:38:44.786  3463  3463 I KnoxTimeoutHandler: Shared devices show user statefalse
,12-07 15:38:44.786  3463  3463 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,12-07 15:38:44.806  3008  3008 I SurfaceFlinger: id=20 createSurf (193x193),1 flag=4, VSBConnecti
,12-07 15:38:44.836  3463  4413 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:44.836  3463  4413 I libsuspend: !@autosuspend_wakeup_count_disable
,12-07 15:38:44.836  3463  4413 D PowerManagerService: mDisplayReady: false
12-07 15:38:44.836  3463  4413 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-07 15:38:44.836  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:44.836  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:38:44.836  3463  4413 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:44.836  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-07 15:38:44.836  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:44.836  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-07 15:38:44.846  3008  3008 I SurfaceFlinger: id=21 createSurf (257x257),1 flag=4, VSBConnecti
12-07 15:38:44.836  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:44.836  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:38:44.836  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:38:44.836  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:38:44.856  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:44.856  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:44.856  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:44.856  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:44.856  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:44.856  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:44.856  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:44.856  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:44.856  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:44.856  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:44.856  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:44.856  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:44.856  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:44.866  3463  3884 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
,12-07 15:38:44.866  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:38:44.866  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:44.876  6182  6182 I TrayVisibilityController: handleMessage : msg.what = 1
,12-07 15:38:44.876  6182  6182 I Utils   : isCurrentUser current = 0, ownerId = 0
12-07 15:38:44.876  6182  6182 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
12-07 15:38:44.886  6182  6182 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,12-07 15:38:44.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:44.906  3463  4339 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:44.906  6518  6518 V ActivityThread: updateVisibility : ActivityRecord{94123c8 token=android.os.BinderProxy@b5ecfd5 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,12-07 15:38:44.966  3463  3884 I MdnieScenarioControlService: mGameModeLauncher : false
,12-07 15:38:44.966  3463  3884 I MdnieScenarioControlService: setUIMode
,12-07 15:38:44.976  3463  4058 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:44.986  3463  3857 V WindowStateAnimator: Finishing drawing window Window{3fa7a36 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,12-07 15:38:44.986  3463  3492 V WindowStateAnimator: Finishing drawing window Window{548b2a4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,12-07 15:38:44.986  6518  6518 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-07 15:38:44.996  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7ff697e338
,12-07 15:38:44.996  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7ff697e338
,12-07 15:38:44.996  3463  4326 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:44.996  3463  3578 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-07 15:38:44.996  3463  3463 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
12-07 15:38:44.996  6518  6518 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-07 15:38:45.006  3463  3578 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +407ms (total +487ms)
,12-07 15:38:45.006  3463  3493 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:45.006  3463  3463 I KnoxTimeoutHandler: SD activityfalse
12-07 15:38:45.006  3463  3578 D ActivityManager: mDVFSHelper.release()
,12-07 15:38:45.006  3463  3578 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9b833e0 u0 com.samsung.android.MtpApplication/.USBConnection t20} time:88681
,12-07 15:38:45.056  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7ff697e338
,12-07 15:38:45.056  3463  3974 V WindowStateAnimator: Finishing drawing window Window{3fa7a36 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,12-07 15:38:45.056  3463  4443 V WindowStateAnimator: Finishing drawing window Window{548b2a4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,12-07 15:38:45.066  6518  6518 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b5ecfd5 time:88740
,12-07 15:38:45.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:45.146  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463 (0x0)
,12-07 15:38:45.156  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463 (0x0)
,12-07 15:38:45.156  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:45.156  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:38:45.156  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-07 15:38:45.156  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:45.156  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:45.156  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:45.156  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
12-07 15:38:45.156  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:45.156  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:38:45.156  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:38:45.156  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-07 15:38:45.156  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:38:45.156  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:38:45.176  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:45.176  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:45.176  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:45.176  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:45.176  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:45.176  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:45.176  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:45.176  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:45.176  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:45.176  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:45.176  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:45.176  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:45.176  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:45.196  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:38:45.196  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:45.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:45.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:45.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:45.616  3463  6436 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,12-07 15:38:45.786  4024  4024 D Recents : onTaskStackChanged
,12-07 15:38:45.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:45.966  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:38:45.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:46.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:46.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:46.396  3463  4989 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:46.396  3463  4989 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:46.396  3463  4989 D PowerManagerService: mDisplayReady: false
12-07 15:38:46.396  3463  4989 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-07 15:38:46.396  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:46.396  3463  4989 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:46.396  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:46.396  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-07 15:38:46.396  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:46.396  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:38:46.396  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:38:46.396  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:38:46.406  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:38:46.406  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-07 15:38:46.436  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:46.436  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:46.436  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:46.436  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:46.436  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:46.436  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:46.436  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:46.436  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:46.436  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:46.436  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:38:46.436  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:46.436  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
12-07 15:38:46.436  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:46.436  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:46.436  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:46.436  3463  4990 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463
,12-07 15:38:46.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:46.596  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3463 (0x0)
,12-07 15:38:46.596  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:46.596  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:38:46.596  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:38:46.596  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:38:46.596  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:46.596  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:46.596  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
,12-07 15:38:46.596  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:46.596  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:38:46.596  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:38:46.596  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-07 15:38:46.596  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:38:46.596  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:38:46.636  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:46.636  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:46.636  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:46.636  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:46.636  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:46.636  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:46.636  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:46.636  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-07 15:38:46.636  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:46.636  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:38:46.636  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:46.636  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:46.636  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:46.646  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:38:46.646  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:46.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:46.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:47.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:47.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:47.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:47.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:47.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:47.846  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:38:47.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:48.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:48.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:48.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:48.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:48.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:49.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:49.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:49.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:49.496  3463  3857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:38:49.496  3463  3857 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:38:49.496  3463  3857 D BatteryService: online:4, current avg:204, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:210
12-07 15:38:49.496  3463  3857 D BatteryService: stay LED for charging
,12-07 15:38:49.496  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:38:49.506  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:38:49.506  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:38:49.506  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:38:49.506  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:38:49.506  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:38:49.516  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:38:49.516  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
12-07 15:38:49.516  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:38:49.516  3952  3952 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-07 15:38:49.516  3952  3952 D PowerUI.Notification: There is no change about charging status, so return!
,12-07 15:38:49.536  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:38:49.536  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:38:49.536  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:38:49.546  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:38:49.546  4719  4719 D BatteryController: saveBatteryData : level[100], status[2]
,12-07 15:38:49.556  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:49.556  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-07 15:38:49.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:49.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:49.896  3463  6435 D SSRM:n  : SIOP:: AP = 310, PST = 394 (W:9), CP = 267, CUR = 204, LCD = 1
,12-07 15:38:49.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:50.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:50.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:50.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:50.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:50.656  3463  6435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-07 15:38:50.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:51.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:51.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:51.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:51.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:51.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:51.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:52.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:52.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:52.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:52.616  8564  8587 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,12-07 15:38:52.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:52.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:52.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:53.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:53.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:53.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:53.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:53.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:54.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:54.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:54.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:54.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:54.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:54.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:55.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:55.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:55.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:55.536  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:38:55.566  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dec03c2 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
,12-07 15:38:55.586  3463  4990 V AlarmManager:  remove PendingIntent] PendingIntent{aee5d3: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
,12-07 15:38:55.656  4327  4334 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@432406)
,12-07 15:38:55.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:55.686  3463  4413 V AlarmManager:  remove PendingIntent] PendingIntent{75f4809: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
,12-07 15:38:55.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:55.876  4327  9340 I VacuumService: Vacuum at: now=1481121535878 tag=VacuumService
,12-07 15:38:55.996  3463  4063 V AlarmManager:  remove PendingIntent] PendingIntent{2adb23c: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
,12-07 15:38:56.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:56.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:56.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:56.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:56.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:56.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:57.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:57.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:57.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:57.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:57.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:58.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:58.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:58.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:58.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:58.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:58.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:59.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:59.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:59.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:59.566  3463  4062 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:38:59.566  3463  4062 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:38:59.566  3463  4062 D BatteryService: online:4, current avg:201, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:223
12-07 15:38:59.566  3463  4062 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3463) 
12-07 15:38:59.566  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:38:59.566  3463  4062 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,12-07 15:38:59.566  3463  4062 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,12-07 15:38:59.566  3463  3588 D LightsService: [SvcLED]  onSensorChanged::light value = 0
12-07 15:38:59.566  3463  3463 I MotionRecognitionService: Plugged
12-07 15:38:59.566  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:38:59.576  3463  4062 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-07 15:38:59.576  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-07 15:38:59.576  3463  3588 D SensorManager: unregisterListener ::   
12-07 15:38:59.576  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
12-07 15:38:59.576  3463  3588 D lights  : led_pattern : 5 +
12-07 15:38:59.576  3463  4062 D BatteryService: turn on LED for fully charged
,12-07 15:38:59.576  3463  3588 D lights  : led_pattern : 5 -
,12-07 15:38:59.576  3463  3588 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-07 15:38:59.576  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-07 15:38:59.576  3463  3588 V AlarmManager:  remove PendingIntent] PendingIntent{1fc6c2a: PendingIntentRecord{3eb0a1b android broadcastIntent}}
,12-07 15:38:59.576  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:38:59.576  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:38:59.586  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:38:59.586  3952  3952 D PowerUI.Notification: dismissChargingNotification()
,12-07 15:38:59.586  3463  3463 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3463) 
,12-07 15:38:59.596  3463  3463 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,12-07 15:38:59.596  3463  3463 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,12-07 15:38:59.596  3463  3463 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-07 15:38:59.596  3463  3463 D EdgeLight: Turning off
,12-07 15:38:59.616  4153  4164 D CatchNotificationsService: onNotificationRemoved
12-07 15:38:59.616  4153  4164 D CatchNotificationsService: Notification removed
,12-07 15:38:59.616  4167  4175 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
,12-07 15:38:59.616  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-07 15:38:59.616  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
,12-07 15:38:59.616  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-07 15:38:59.616  4167  4167 I PeopleDataManager: removeNotification
,12-07 15:38:59.616  4167  4167 I NotificationParser: getNotiType:android,led_indicator
,12-07 15:38:59.616  4167  4167 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-07 15:38:59.616  4167  4167 D PeopleDataManager: removeNotiInfo =null
,12-07 15:38:59.616  3952  3952 D PhoneStatusBar: removeNotification key=-1|com.android.systemui|2131624021|charging_state|10065 old=StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=2131624021 tag=charging_state score=-20 key=-1|com.android.systemui|2131624021|charging_state|10065: Notification(pri=-2 contentView=com.android.systemui/0x10900a3 vibrate=null sound=null defaults=0x0 flags=0xa color=0xff7792a9 category=sys vis=PUBLIC secFlags=0x0 secPriority=0))
,12-07 15:38:59.626  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:38:59.616  3952  3952 D PhoneStatusBar: setAreThereNotifications: N=2 any=true clearable=false
12-07 15:38:59.626  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:38:59.616  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:38:59.626  4167  4175 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.systemui,id=2131624021,extra=Bundle[mParcelledData.dataSize=84]
12-07 15:38:59.626  4167  4167 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=2131624021, samsung.notification.type=normal, samsung.people.package_name=com.android.systemui}]
12-07 15:38:59.626  4167  4167 I PeopleStripeService: PeopleNotificationReceiver:3
12-07 15:38:59.626  4167  4167 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,12-07 15:38:59.626  4167  4167 I PeopleDataManager: removeNotification
12-07 15:38:59.626  4167  4167 I NotificationParser: getNotiType:com.android.systemui,null
,12-07 15:38:59.636  6182  6182 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-07 15:38:59.626  4167  4167 D PeopleDataManager: removeNotiInfo: id =2131624021,packageName=com.android.systemui,isEdgeNotification=false,key=null,removeAll=false
12-07 15:38:59.626  4167  4167 D PeopleDataManager: removeNotiInfo =null
12-07 15:38:59.626  6182  6182 I CocktailBarUiController: onUpdateCocktail: 2
12-07 15:38:59.626  6182  6182 I CocktailBarPanelManager: updatePanelItem: updateContainedPanel - 2
12-07 15:38:59.626  6182  6182 D CatchNotificationsView: setData
,12-07 15:38:59.626  6182  6182 D CatchNotificationsView: Notification removed
12-07 15:38:59.626  6182  6182 D CatchNotificationsView: No notifications left to remove
12-07 15:38:59.626  6182  6182 D CatchNotificationsView: makeNoNotificationsPanel
12-07 15:38:59.626  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:38:59.626  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-07 15:38:59.636  6182  6182 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
,12-07 15:38:59.636  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:38:59.636  6182  6182 D PanelDescriptionView: updateHelpView: Apps edge2130903041 --> 2130903041 helpview reapplied:0
12-07 15:38:59.636  6182  6182 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
,12-07 15:38:59.636  6182  6182 D CocktailBarUiController: postUpdatePanel: 257
,12-07 15:38:59.636  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:38:59.636  4719  4719 D AODService: Received intent, service updating android.intent.action.BATTERY_CHANGED
,12-07 15:38:59.646  3463  4063 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:59.646  3463  4063 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:38:59.646  3463  4063 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:38:59.646  3463  4063 D PowerManagerService: mDisplayReady: false
12-07 15:38:59.646  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:38:59.646  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:59.646  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-07 15:38:59.646  3463  4063 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:38:59.646  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:59.646  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:59.646  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:59.646  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:38:59.646  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,12-07 15:38:59.646  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
12-07 15:38:59.646  3463  3588 D SensorManager: unregisterListener ::   
12-07 15:38:59.646  3463  3588 D LightsService: [SvcLED]  onSensorChanged::light value = 0
12-07 15:38:59.646  3463  3588 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-07 15:38:59.646  3463  3588 V AlarmManager:  remove PendingIntent] PendingIntent{1fc6c2a: PendingIntentRecord{3eb0a1b android broadcastIntent}}
,12-07 15:38:59.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:59.656  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:59.656  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:59.656  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:59.656  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:59.656  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:59.656  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:59.656  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:38:59.656  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:38:59.656  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:59.656  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:59.656  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:59.656  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:59.656  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:59.666  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:38:59.666  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:59.666  3463  4326 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:38:59.676  4719  4719 D BatteryMeterView: onDraw batteryColor : -986896
,12-07 15:38:59.676  3463  4152 E Watchdog: !@Sync 3 [12-07 15:38:59.682]
,12-07 15:38:59.816  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
,12-07 15:38:59.816  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:38:59.816  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:38:59.816  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:38:59.826  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-07 15:38:59.826  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:59.826  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:59.826  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-07 15:38:59.826  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
12-07 15:38:59.826  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:38:59.826  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:38:59.826  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-07 15:38:59.826  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:38:59.826  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:38:59.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:38:59.856  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:38:59.856  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:59.856  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:38:59.856  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:59.856  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:38:59.856  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:38:59.856  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:38:59.856  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:38:59.856  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:38:59.856  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:38:59.856  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:38:59.856  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:38:59.856  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:38:59.866  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:38:59.866  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:38:59.916  3463  6435 D SSRM:n  : SIOP:: AP = 300, PST = 385 (W:10), CP = 263, CUR = 201, LCD = 1
,12-07 15:38:59.996  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:39:00.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:00.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:00.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:00.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:00.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:00.796  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:39:00.796  3463  3820 V AlarmManager: Send whitelist package alarm :PendingIntent{2c40203: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:39:00.796  3463  3463 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,12-07 15:39:00.796  3463  3463 V AlarmManagerEXT: <AppSync3 Whitelist>
,12-07 15:39:00.796  3463  3463 V AlarmManagerEXT: (AppSync) ### 0 added ###
,12-07 15:39:00.806  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-07 15:39:00.806  3952  3952 D KeyguardUpdateMonitor: handleTimeUpdate
,12-07 15:39:00.826  3952  3952 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-07 15:39:00.886  3952  3952 D DateView: received broadcast android.intent.action.TIME_TICK
,12-07 15:39:00.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:00.916  8014  8014 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-07 15:39:00.916  8014  8014 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-07 15:39:00.926  4719  4719 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-07 15:39:00.926  4719  4719 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-07 15:39:00.936  3463  4339 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:39:00.936  3463  4339 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,12-07 15:39:00.936  3463  4339 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-07 15:39:00.936  3463  4339 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,12-07 15:39:00.936  3169  3213 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-07 15:39:00.946  3463  4339 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-07 15:39:00.946  3463  4339 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-07 15:39:00.946  3463  4339 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
,12-07 15:39:00.946  4719  4719 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e89b19, service=Device Physical Context Monitor
12-07 15:39:00.946  4719  4719 I AlpmModeManager: startAlpmMode : state  = BLANK
12-07 15:39:00.946  4719  4719 D DefaultClockView: Window showed. Time views updating
,12-07 15:39:00.946  3463  4062 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:39:00.946  3463  4062 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:39:00.946  3463  4062 D PowerManagerService: mDisplayReady: false
12-07 15:39:00.946  3463  4062 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:39:00.946  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:39:00.946  4719  4719 D AODUpdatePositionController: updatePosition: direction[5] updatePosition: X[-2] Y[397] NewPositionTimer[58]
12-07 15:39:00.946  3463  4062 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:39:00.946  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-07 15:39:00.946  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:39:00.946  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
,12-07 15:39:00.946  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:39:00.946  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-07 15:39:00.946  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:39:00.946  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:39:00.956  4719  4719 D DefaultClockView: LocalTime Pattern : HH:mm
,12-07 15:39:00.946  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:39:00.956  4719  4719 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 15:39 time02: null ampm: null
,12-07 15:39:00.966  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:39:00.966  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:39:00.966  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:39:00.966  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:39:00.966  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:39:00.966  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:39:00.966  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:39:00.966  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:39:00.966  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:39:00.966  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:39:00.966  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:39:00.966  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:39:00.966  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:39:00.966  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:39:00.966  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:39:00.966  3169  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-07 15:39:00.966  3463  3823 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-07 15:39:00.966  3463  3822 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 39, 0,
,12-07 15:39:00.966  3463  3822 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 39, 0
12-07 15:39:00.966  3169  7762 D Sensorhubs: sendContextData: -63, 14, 14, 39, 0
,12-07 15:39:00.966  4719  4719 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-07 15:39:00.976  4719  4719 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-07 15:39:00.976  4719  4719 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:śr., 7 gru 15:39
12-07 15:39:00.976  4719  4719 I AODService.ClockTimer: startAlarm : TICK
,12-07 15:39:00.976  3463  3492 V AlarmManager: Add whitelist package alarm :PendingIntent{2033c4b: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:39:00.976  3463  3822 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
12-07 15:39:00.976  3463  3822 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-07 15:39:00.976  3463  3822 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
12-07 15:39:00.976  3463  3822 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-07 15:39:00.976  4719  4719 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
12-07 15:39:00.976  3463  4637 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
,12-07 15:39:00.976  4719  4719 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-07 15:39:00.976  3463  4637 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
12-07 15:39:00.976  3463  3822 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-07 15:39:00.976  3463  4989 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:39:00.986  3463  3825 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-07 15:39:00.986  4719  4719 D DefaultClockView: RootView invalidate()
,12-07 15:39:00.986  3463  4432 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:39:00.986  4719  4719 I AODService: onSContextChanged: AODScreenShown state is already true
,12-07 15:39:01.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:01.136  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
,12-07 15:39:01.136  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:39:01.136  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:39:01.136  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:39:01.136  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:39:01.136  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:39:01.136  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:39:01.136  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:39:01.136  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
,12-07 15:39:01.136  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:39:01.136  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-07 15:39:01.136  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-07 15:39:01.136  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:39:01.136  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:39:01.166  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:39:01.166  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:39:01.166  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:39:01.166  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:39:01.166  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:39:01.166  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:39:01.166  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:39:01.166  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:39:01.166  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:39:01.166  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:39:01.166  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:39:01.166  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:39:01.166  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:39:01.186  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:39:01.186  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:39:01.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:01.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:01.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:01.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:01.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:02.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:02.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:02.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:02.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:02.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:03.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:03.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:03.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:03.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:03.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:03.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:04.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:04.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:04.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:04.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:04.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:05.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:05.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:05.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:05.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:05.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:05.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:06.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:06.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:06.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:06.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:06.726  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:39:06.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:07.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:07.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:07.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:07.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:07.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:07.846  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:39:07.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:08.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:08.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:08.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:08.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:08.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.616  3463  4062 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:39:09.616  3463  4062 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:39:09.616  3463  4062 D BatteryService: online:4, current avg:194, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:189
12-07 15:39:09.616  3463  4062 D BatteryService: stay LED for fully charged
,12-07 15:39:09.616  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:39:09.626  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:39:09.626  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:39:09.626  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:39:09.626  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:39:09.626  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-07 15:39:09.636  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:39:09.636  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:39:09.636  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:39:09.656  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:39:09.656  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:39:09.656  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:39:09.666  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:39:09.666  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:39:09.676  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:09.686  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:09.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:09.936  3463  6435 D SSRM:n  : SIOP:: AP = 300, PST = 369 (W:10), CP = 260, CUR = 194, LCD = 1
,12-07 15:39:10.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:10.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:10.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:10.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:10.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:10.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:11.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:11.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:11.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:11.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:11.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:12.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:12.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:12.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:12.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:12.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:12.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:13.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:13.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:13.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:13.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:13.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:14.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:14.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:14.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:14.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:14.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:14.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:15.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:15.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:15.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:15.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:15.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:16.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:16.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:16.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:16.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:16.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:16.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:17.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:17.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:17.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:17.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:17.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:18.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:18.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:18.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:18.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:18.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:18.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:19.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:19.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:19.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:19.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:19.676  3463  4431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:39:19.676  3463  4431 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:39:19.676  3463  4431 D BatteryService: online:4, current avg:191, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:186
12-07 15:39:19.676  3463  4431 D BatteryService: stay LED for fully charged
12-07 15:39:19.676  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:39:19.686  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:39:19.686  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:39:19.686  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:39:19.686  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:39:19.696  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:39:19.696  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:39:19.696  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:39:19.696  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:39:19.716  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:39:19.716  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:39:19.716  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:39:19.726  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:39:19.726  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:39:19.726  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:39:19.726  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:19.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:19.966  3463  6435 D SSRM:n  : SIOP:: AP = 300, PST = 350 (W:10), CP = 258, CUR = 191, LCD = 1
,12-07 15:39:19.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:20.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:20.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:20.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:20.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:20.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:21.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:21.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:21.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:21.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:21.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:21.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:22.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:22.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:22.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:22.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:22.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:23.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:23.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:23.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:23.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:23.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:23.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:24.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:24.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:24.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:24.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:24.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:25.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:25.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:25.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:25.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:25.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:25.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:26.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:26.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:26.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:26.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:26.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:27.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:27.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:27.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:27.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:27.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:27.846  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:39:27.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:28.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:28.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:28.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:28.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:28.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:28.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:29.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:29.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:29.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:29.676  3463  4152 E Watchdog: !@Sync 4 [12-07 15:39:29.684]
,12-07 15:39:29.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:29.746  3463  4326 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:39:29.746  3463  4326 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:39:29.746  3463  4326 D BatteryService: online:4, current avg:185, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:197
12-07 15:39:29.746  3463  4326 D BatteryService: stay LED for fully charged
,12-07 15:39:29.746  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:39:29.746  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:39:29.746  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:39:29.746  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:39:29.746  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:39:29.756  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:39:29.756  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:39:29.756  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:39:29.756  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:39:29.776  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:39:29.776  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:39:29.776  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:39:29.786  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:39:29.786  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:39:29.806  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:29.806  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:29.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:29.986  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 330 (W:10), CP = 257, CUR = 185, LCD = 1
,12-07 15:39:30.006  3463  6435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-07 15:39:30.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:30.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:30.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:30.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:30.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:30.916  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-07 15:39:30.916  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-07 15:39:30.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:31.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:31.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:31.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:31.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:31.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:32.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:32.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:32.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:32.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:32.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:32.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:33.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:33.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:33.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:33.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:33.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:34.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:34.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:34.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:34.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:34.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:34.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:35.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:35.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:35.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:35.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:35.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:36.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:36.156  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:39:36.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:36.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:36.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:36.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:36.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:37.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:37.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:37.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:37.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:37.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:37.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:38.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:38.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:38.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:38.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:38.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:39.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:39.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:39.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:39.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:39.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:39.806  3463  4443 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:39:39.806  3463  4443 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:39:39.806  3463  4443 D BatteryService: online:4, current avg:177, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:181
12-07 15:39:39.806  3463  4443 D BatteryService: stay LED for fully charged
12-07 15:39:39.806  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:39:39.806  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:39:39.806  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:39:39.806  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:39:39.806  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:39:39.816  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:39:39.816  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:39:39.816  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:39:39.816  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:39:39.836  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:39:39.836  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:39:39.836  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:39:39.846  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:39:39.846  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:39:39.856  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:39.856  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:39.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:40.036  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 313 (W:10), CP = 255, CUR = 177, LCD = 1
,12-07 15:39:40.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:40.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:40.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:40.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:40.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:41.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:41.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:41.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:41.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:41.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:41.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:42.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:42.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:42.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:42.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:42.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:43.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:43.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:43.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:43.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:43.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:43.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:44.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:44.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:44.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:44.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:44.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:45.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:45.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:45.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:45.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:45.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:45.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:46.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:46.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:46.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:46.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:46.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:46.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:47.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:47.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:47.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:47.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:47.846  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:39:47.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:48.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:48.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:48.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:48.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:48.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:48.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:49.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:49.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:49.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:49.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:49.866  3463  3857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:39:49.866  3463  3857 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:39:49.866  3463  3857 D BatteryService: online:4, current avg:173, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:165
12-07 15:39:49.866  3463  3857 D BatteryService: stay LED for fully charged
12-07 15:39:49.866  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:39:49.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:49.866  3463  3463 I MotionRecognitionService: Plugged
12-07 15:39:49.866  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:39:49.866  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:39:49.866  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:39:49.876  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:39:49.876  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:39:49.876  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:39:49.886  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:39:49.896  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:39:49.906  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:39:49.906  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:39:49.916  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:39:49.916  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:39:49.936  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:49.936  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:50.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:50.056  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 305 (W:14), CP = 254, CUR = 173, LCD = 1
,12-07 15:39:50.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:50.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:50.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:50.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:50.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:51.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:51.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:51.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:51.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:51.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:52.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:52.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:52.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:52.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:52.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:52.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:53.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:53.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:53.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:53.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:53.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:54.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:54.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:54.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:54.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:54.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:54.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:55.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:55.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:55.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:55.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:55.636  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:39:55.666  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{433dce6 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
,12-07 15:39:55.696  9349  9349 E Zygote  : v2
12-07 15:39:55.696  9349  9349 I libpersona: KNOX_SDCARD checking this for 1000
12-07 15:39:55.696  9349  9349 I libpersona: KNOX_SDCARD not a persona
,12-07 15:39:55.696  9349  9349 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
,12-07 15:39:55.696  3463  3820 I ActivityManager: Start proc 9349:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,12-07 15:39:55.706  9349  9349 E Zygote  : accessInfo : 0
,12-07 15:39:55.716  3463  4339 V AlarmManager:  remove PendingIntent] PendingIntent{7475227: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
,12-07 15:39:55.736  9349  9349 D TimaKeyStoreProvider: TimaSignature is unavailable
12-07 15:39:55.736  9349  9349 D ActivityThread: Added TimaKeyStore provider
,12-07 15:39:55.756  9349  9349 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-07 15:39:55.756  9349  9349 D RelationGraph: garbageCollect()
,12-07 15:39:55.766  9349  9349 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,12-07 15:39:55.766  3463  3857 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-07 15:39:55.766  9349  9349 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-07 15:39:55.766  9349  9349 D ResourcesManager: For user 0 new overlays fetched Null
,12-07 15:39:55.766  9349  9349 I InjectionManager: Inside getClassLibPath caller 
,12-07 15:39:55.776  9349  9349 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,12-07 15:39:55.776  9349  9349 D InjectionManager: InjectionManager
12-07 15:39:55.776  9349  9349 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,12-07 15:39:55.776  9349  9349 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
12-07 15:39:55.776  9349  9349 I InjectionManager: featureStore :{}
,12-07 15:39:55.806  3463  4413 I ActivityManager: Killing 6028:com.sec.android.provider.badge/u0a4 (adj 15): DHA:empty #33
,12-07 15:39:55.806  4577  9361 D UdcContextInitService: registered all accounts: true
12-07 15:39:55.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:55.826  3463  4990 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,12-07 15:39:55.906  3463  4062 V AlarmManager:  remove PendingIntent] PendingIntent{9d0e172: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
,12-07 15:39:55.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:56.136  4327  9367 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 5414 seconds from now (1481121596140)
,12-07 15:39:56.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:39:56.166  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d72cca u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73fde3b 4327:com.google.android.gms.persistent/u0a21}
,12-07 15:39:56.226  4327  9365 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-07 15:39:56.226  4327  9365 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-07 15:39:56.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:56.496  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:39:56.496  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-07 15:39:56.506  3154  3640 D EnterpriseController: netId is 0
12-07 15:39:56.506  3154  3640 D Netd    : getNetworkForDns: using netid 502 for uid 10021
,12-07 15:39:56.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:56.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:56.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:57.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:57.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:57.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:57.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:57.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:57.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:58.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:58.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:58.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:58.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:58.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:59.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:59.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:59.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:59.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:59.676  3463  4152 E Watchdog: !@Sync 5 [12-07 15:39:59.685]
,12-07 15:39:59.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:39:59.926  3463  4989 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:39:59.926  3463  4989 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:39:59.926  3463  4989 D BatteryService: online:4, current avg:160, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:159
12-07 15:39:59.926  3463  4989 D BatteryService: stay LED for fully charged
12-07 15:39:59.926  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:39:59.936  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:39:59.936  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:39:59.936  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:39:59.936  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:39:59.936  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:39:59.946  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:39:59.946  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:39:59.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
12-07 15:39:59.946  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:39:59.966  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:39:59.966  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:39:59.976  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:39:59.976  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:39:59.976  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:39:59.986  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:39:59.986  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:39:59.996  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:40:00.086  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:14), CP = 254, CUR = 160, LCD = 1
,12-07 15:40:00.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:00.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:00.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:00.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:00.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:00.976  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:40:00.976  3463  3820 V AlarmManager: Send whitelist package alarm :PendingIntent{2033c4b: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:40:00.976  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-07 15:40:00.986  3952  3952 D KeyguardUpdateMonitor: handleTimeUpdate
,12-07 15:40:00.996  3952  3952 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-07 15:40:01.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:01.066  3952  3952 D DateView: received broadcast android.intent.action.TIME_TICK
,12-07 15:40:01.096  8014  8014 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-07 15:40:01.096  8014  8014 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-07 15:40:01.106  4719  4719 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,12-07 15:40:01.106  4719  4719 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-07 15:40:01.106  3463  3493 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:40:01.106  3463  3493 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,12-07 15:40:01.106  3463  3493 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
,12-07 15:40:01.106  3463  3493 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-07 15:40:01.106  3169  3169 D Sensorhubs: sendContextData: -72, 56, 1, 1,
,12-07 15:40:01.116  3463  3493 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-07 15:40:01.116  3463  3493 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-07 15:40:01.116  3463  3493 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-07 15:40:01.116  4719  4719 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e89b19, service=Device Physical Context Monitor
12-07 15:40:01.116  4719  4719 I AlpmModeManager: startAlpmMode : state  = BLANK
12-07 15:40:01.116  4719  4719 D DefaultClockView: Window showed. Time views updating
,12-07 15:40:01.116  3463  4063 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:40:01.116  3463  4063 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:40:01.116  3463  4063 D PowerManagerService: mDisplayReady: false
12-07 15:40:01.116  3463  4063 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:40:01.116  3463  4063 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:40:01.126  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-07 15:40:01.126  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:40:01.126  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:40:01.126  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:40:01.126  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:40:01.126  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:40:01.126  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:40:01.126  4719  4719 D AODUpdatePositionController: updatePosition: direction[3] updatePosition: X[-1] Y[396] NewPositionTimer[57]
,12-07 15:40:01.126  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
,12-07 15:40:01.126  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-07 15:40:01.126  4719  4719 D DefaultClockView: LocalTime Pattern : HH:mm
,12-07 15:40:01.136  4719  4719 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 15:40 time02: null ampm: null
,12-07 15:40:01.136  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:40:01.136  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:40:01.136  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
,12-07 15:40:01.136  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:40:01.136  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:40:01.136  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:40:01.136  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:40:01.136  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:40:01.136  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:40:01.136  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:40:01.136  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:40:01.136  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:40:01.136  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:40:01.136  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:40:01.136  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:40:01.146  3169  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-07 15:40:01.146  3463  3823 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-07 15:40:01.146  3463  3822 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 40, 1,
,12-07 15:40:01.146  3463  3822 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 40, 1
12-07 15:40:01.146  3169  3213 D Sensorhubs: sendContextData: -63, 14, 14, 40, 1
,12-07 15:40:01.146  4719  4719 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-07 15:40:01.146  4719  4719 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-07 15:40:01.146  3463  3822 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
12-07 15:40:01.146  3463  3822 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-07 15:40:01.146  4719  4719 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:śr., 7 gru 15:40
12-07 15:40:01.146  4719  4719 I AODService.ClockTimer: startAlarm : TICK
12-07 15:40:01.146  3463  3822 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
12-07 15:40:01.146  3463  4058 V AlarmManager: Add whitelist package alarm :PendingIntent{438c0ed: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
12-07 15:40:01.146  3463  3822 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-07 15:40:01.146  3463  3822 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
12-07 15:40:01.146  3463  3825 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-07 15:40:01.156  4719  4719 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-07 15:40:01.156  4719  4719 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-07 15:40:01.156  3463  4339 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-07 15:40:01.156  3463  4339 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-07 15:40:01.156  4719  4719 D DefaultClockView: RootView invalidate()
12-07 15:40:01.156  3463  4431 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:40:01.156  4719  4719 I AODService: onSContextChanged: AODScreenShown state is already true
,12-07 15:40:01.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:01.306  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
12-07 15:40:01.306  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:40:01.306  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:40:01.306  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:40:01.306  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:40:01.306  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:40:01.306  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:40:01.306  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:40:01.306  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:40:01.316  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-07 15:40:01.316  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:40:01.316  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
12-07 15:40:01.316  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:40:01.316  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:40:01.336  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:40:01.336  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:40:01.336  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:40:01.336  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:40:01.336  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:40:01.336  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:40:01.336  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:40:01.336  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:40:01.336  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:40:01.336  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:40:01.336  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:40:01.336  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:40:01.336  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:40:01.346  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:40:01.346  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:40:01.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:01.546  4327  9365 I qtaguid : Tagging socket 60 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:01.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:01.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:01.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:02.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:02.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:02.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:02.576  4327  9365 I qtaguid : Tagging socket 66 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:02.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:02.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:03.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:03.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:03.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:03.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:03.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:03.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:04.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:04.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:04.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:04.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:04.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:04.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:05.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:05.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:05.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:05.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:05.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:06.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:06.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:06.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:06.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:06.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:06.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:07.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:07.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:07.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:07.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:07.856  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:40:07.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:08.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:08.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:08.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:08.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:08.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:08.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:09.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:09.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:09.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:09.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:09.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:09.986  3463  4413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:40:09.986  3463  4413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:40:09.986  3463  4413 D BatteryService: online:4, current avg:158, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:188
12-07 15:40:09.986  3463  4413 D BatteryService: stay LED for fully charged
12-07 15:40:09.986  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:40:09.996  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:40:09.996  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:40:09.996  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:40:09.996  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:40:09.996  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:40:09.996  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:40:10.006  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:40:10.006  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:40:10.016  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:40:10.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:10.026  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:40:10.026  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:40:10.036  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:40:10.036  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:40:10.056  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:10.056  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:10.116  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:14), CP = 253, CUR = 158, LCD = 1
,12-07 15:40:10.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:10.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:10.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:10.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:10.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:11.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:11.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:11.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:11.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:11.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:12.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:12.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:12.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:12.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:12.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:12.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:13.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:13.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:13.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:13.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:13.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:13.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:14.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:14.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:14.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:14.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:14.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:15.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:15.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:15.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:15.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:15.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:15.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:16.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:16.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:16.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:16.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:16.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:17.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:17.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:17.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:17.456  9375  9375 E Zygote  : v2
12-07 15:40:17.456  9375  9375 I libpersona: KNOX_SDCARD checking this for 1000
12-07 15:40:17.456  9375  9375 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0029
12-07 15:40:17.456  9375  9375 I libpersona: KNOX_SDCARD not a persona
,12-07 15:40:17.456  9375  9375 E Zygote  : accessInfo : 0
,12-07 15:40:17.456  3463  6436 I ActivityManager: Start proc 9375:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.sm.provider/com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider
,12-07 15:40:17.496  9375  9375 D TimaKeyStoreProvider: TimaSignature is unavailable
12-07 15:40:17.496  9375  9375 D ActivityThread: Added TimaKeyStore provider
,12-07 15:40:17.556  9375  9375 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-07 15:40:17.556  9375  9375 D RelationGraph: garbageCollect()
,12-07 15:40:17.556  9375  9375 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManagerProvider/SmartManagerProvider.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.sm.provider
,12-07 15:40:17.566  3463  4339 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-07 15:40:17.566  9375  9375 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-07 15:40:17.566  9375  9375 D ResourcesManager: For user 0 new overlays fetched Null
,12-07 15:40:17.576  9375  9375 I InjectionManager: Inside getClassLibPath caller 
,12-07 15:40:17.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:17.596  9375  9375 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManagerProvider/lib/arm64
,12-07 15:40:17.646  9375  9375 D InjectionManager: InjectionManager
12-07 15:40:17.646  9375  9375 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.provider
,12-07 15:40:17.646  9375  9375 I InjectionManager: Constructor com.samsung.android.sm.provider, Feature store :{}
12-07 15:40:17.646  9375  9375 I InjectionManager: featureStore :{}
,12-07 15:40:17.666  3463  3463 I ActivityManager: Killing 8905:com.sec.android.app.sns3/u0a41 (adj 15): DHA:empty #33
,12-07 15:40:17.666  3463  6436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,12-07 15:40:17.686  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{980376e u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98f4e0f 9375:com.samsung.android.sm.provider/1000}
,12-07 15:40:17.696  3463  4990 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sns3, Auto Run ON
,12-07 15:40:17.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:17.806  3463  6436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,12-07 15:40:17.826  3463  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81620a5 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98f4e0f 9375:com.samsung.android.sm.provider/1000}
,12-07 15:40:17.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:18.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:18.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:18.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:18.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:18.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:19.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:19.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:19.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:19.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:19.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:19.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:20.046  3463  3857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:40:20.046  3463  3857 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:40:20.046  3463  3857 D BatteryService: online:4, current avg:158, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:138
12-07 15:40:20.046  3463  3857 D BatteryService: stay LED for fully charged
,12-07 15:40:20.046  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:40:20.056  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:40:20.056  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:40:20.056  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:40:20.056  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:40:20.056  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:40:20.066  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:40:20.066  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:40:20.066  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:40:20.076  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:40:20.086  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:40:20.086  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:40:20.096  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:40:20.096  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:40:20.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:20.096  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:40:20.096  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:20.136  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:14), CP = 252, CUR = 158, LCD = 1
,12-07 15:40:20.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:20.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:20.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:20.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:21.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:21.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:21.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:21.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:21.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:21.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:22.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:22.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:22.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:22.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:22.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:22.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:23.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:23.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:23.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:23.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:23.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:24.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:24.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:24.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:24.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:24.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:24.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:25.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:25.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:25.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:25.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:25.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:26.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:26.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:26.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:26.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:26.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:26.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:27.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:27.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:27.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:27.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:27.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:27.856  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:40:28.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:28.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:28.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:28.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:28.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:28.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:29.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:29.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:29.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:29.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:29.686  3463  4152 E Watchdog: !@Sync 6 [12-07 15:40:29.687]
,12-07 15:40:29.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:29.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:30.106  3463  4443 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:40:30.106  3463  4443 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:40:30.106  3463  4443 D BatteryService: online:4, current avg:155, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:147
12-07 15:40:30.106  3463  4443 D BatteryService: stay LED for fully charged
12-07 15:40:30.106  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:40:30.116  3463  3463 I MotionRecognitionService: Plugged
12-07 15:40:30.116  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:40:30.116  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:40:30.116  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:40:30.116  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:40:30.126  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:40:30.126  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:40:30.126  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:40:30.136  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:40:30.146  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:40:30.146  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:40:30.156  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:40:30.156  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:30.156  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:30.156  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:40:30.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:30.176  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:14), CP = 251, CUR = 155, LCD = 1
,12-07 15:40:30.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:30.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:30.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:30.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:31.026  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-07 15:40:31.026  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-07 15:40:31.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:31.136  4399  4467 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 103ms lastUpdatedAfter : 127054ms
,12-07 15:40:31.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:31.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:31.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:31.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:31.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:32.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:32.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:32.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:32.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:32.716  4327  9365 I qtaguid : Untagging socket 60
,12-07 15:40:32.716  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:32.716  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:32.716  4327  9365 I qtaguid : Tagging socket 60 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:32.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:33.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:33.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:33.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:33.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:33.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:33.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:34.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:34.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:34.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:34.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:34.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:35.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:35.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:35.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:35.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:35.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:35.776  4327  9365 I qtaguid : Tagging socket 67 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:35.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:36.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:36.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:36.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:36.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:36.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:37.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:37.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:37.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:37.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:37.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:37.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:38.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:38.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:38.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:38.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:38.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:38.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:39.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:39.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:39.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:39.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:39.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:40.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:40.166  3463  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:40:40.166  3463  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:40:40.166  3463  4339 D BatteryService: online:4, current avg:153, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:149
12-07 15:40:40.166  3463  4339 D BatteryService: stay LED for fully charged
12-07 15:40:40.166  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:40:40.176  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:40:40.176  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:40:40.176  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:40:40.176  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:40:40.176  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:40:40.186  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:40:40.186  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:40:40.186  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:40:40.196  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:40:40.206  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:40:40.206  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:40:40.216  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:40:40.216  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:40:40.216  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:14), CP = 251, CUR = 153, LCD = 1
,12-07 15:40:40.226  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:40:40.226  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:40.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:40.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:40.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:40.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:40.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:41.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:41.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:41.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:41.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:41.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:42.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:42.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:42.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:42.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:42.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:42.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:43.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:43.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:43.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:43.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:43.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:44.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:44.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:44.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:44.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:44.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:44.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:45.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:45.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:45.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:45.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:45.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:46.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:46.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:46.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:46.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:46.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:46.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:47.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:47.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:47.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:47.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:47.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:47.856  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:40:47.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:48.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:48.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:48.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:48.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:48.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:49.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:49.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:49.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:49.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:49.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:49.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:50.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:50.226  3463  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:40:50.226  3463  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:40:50.226  3463  4339 D BatteryService: online:4, current avg:149, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:141
12-07 15:40:50.226  3463  4339 D BatteryService: stay LED for fully charged
,12-07 15:40:50.226  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:40:50.236  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:40:50.236  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:40:50.236  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:40:50.236  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:40:50.236  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:40:50.246  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:40:50.246  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
12-07 15:40:50.246  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:40:50.266  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, CUR = 149, LCD = 1
,12-07 15:40:50.266  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:40:50.276  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:50.276  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:40:50.286  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:40:50.286  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:40:50.286  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:40:50.286  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:40:50.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:50.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:50.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:50.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:51.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:51.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:51.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:51.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:51.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:51.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:52.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:52.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:52.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:52.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:52.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:53.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:53.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:53.296  4327  9365 I qtaguid : Untagging socket 60
,12-07 15:40:53.296  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:53.296  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:53.296  4327  9365 I qtaguid : Tagging socket 60 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:53.336  4327  9365 I qtaguid : Tagging socket 68 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:53.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:53.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:53.616  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:53.616  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:53.616  4327  9365 I qtaguid : Tagging socket 60 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:53.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:53.916  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:53.916  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:53.916  4327  9365 I qtaguid : Tagging socket 60 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:53.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:54.046  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:54.046  4327  9365 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-07 15:40:54.046  4327  9365 I qtaguid : Tagging socket 60 with tag 1000120100000000{268440065,0} uid -1, pid: 4327, getuid(): 10021
,12-07 15:40:54.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:54.216  3463  4432 V AlarmManager:  remove PendingIntent] PendingIntent{188f007: PendingIntentRecord{6cad75a com.google.android.gms broadcastIntent}}
,12-07 15:40:54.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:54.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:54.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:54.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:55.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:55.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:55.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:55.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:55.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:55.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:56.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:56.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:56.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:56.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:56.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:56.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:57.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:57.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:57.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:57.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:57.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:58.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:58.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:58.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:58.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:58.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:58.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:59.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:59.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:59.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:59.686  3463  4152 E Watchdog: !@Sync 7 [12-07 15:40:59.689]
,12-07 15:40:59.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:59.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:40:59.996  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:41:00.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:00.146  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:41:00.156  3463  3820 V AlarmManager: Send whitelist package alarm :PendingIntent{438c0ed: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:41:00.156  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-07 15:41:00.156  3952  3952 D KeyguardUpdateMonitor: handleTimeUpdate
,12-07 15:41:00.176  3952  3952 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-07 15:41:00.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:00.246  3952  3952 D DateView: received broadcast android.intent.action.TIME_TICK
,12-07 15:41:00.276  8014  8014 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-07 15:41:00.286  8014  8014 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-07 15:41:00.286  3463  4058 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:41:00.286  3463  4058 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:41:00.286  3463  4058 D BatteryService: online:4, current avg:142, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:157
12-07 15:41:00.286  4719  4719 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-07 15:41:00.286  3463  4058 D BatteryService: stay LED for fully charged
12-07 15:41:00.286  4719  4719 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
12-07 15:41:00.286  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:41:00.296  3463  4443 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:41:00.296  3463  4443 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-07 15:41:00.296  3463  4443 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-07 15:41:00.296  3463  4443 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-07 15:41:00.296  3169  7762 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-07 15:41:00.296  3463  3463 I MotionRecognitionService: Plugged
12-07 15:41:00.296  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:41:00.296  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:41:00.296  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:41:00.306  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:41:00.306  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:41:00.306  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:41:00.306  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:41:00.306  3463  4443 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-07 15:41:00.306  3463  4443 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-07 15:41:00.306  3463  4443 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
,12-07 15:41:00.306  4719  4719 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e89b19, service=Device Physical Context Monitor
12-07 15:41:00.306  4719  4719 I AlpmModeManager: startAlpmMode : state  = BLANK
12-07 15:41:00.306  4719  4719 D DefaultClockView: Window showed. Time views updating
12-07 15:41:00.306  3463  3493 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:41:00.306  3463  3493 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:41:00.306  3463  3493 D PowerManagerService: mDisplayReady: false
12-07 15:41:00.306  3463  3493 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:41:00.306  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:41:00.306  4719  4719 D AODUpdatePositionController: updatePosition: direction[3] updatePosition: X[0] Y[395] NewPositionTimer[56]
12-07 15:41:00.306  3463  3493 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:41:00.306  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:41:00.306  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:41:00.306  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-07 15:41:00.306  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:41:00.306  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:41:00.306  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:41:00.306  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:41:00.306  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:41:00.316  4719  4719 D DefaultClockView: LocalTime Pattern : HH:mm
,12-07 15:41:00.326  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, CUR = 142, LCD = 1
,12-07 15:41:00.326  4719  4719 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 15:41 time02: null ampm: null
,12-07 15:41:00.326  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-07 15:41:00.326  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:41:00.326  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:41:00.326  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:41:00.326  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:41:00.326  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:41:00.326  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:41:00.326  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-07 15:41:00.326  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:41:00.326  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:41:00.326  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-07 15:41:00.326  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:41:00.326  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:41:00.336  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:41:00.336  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:41:00.336  4719  4719 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-07 15:41:00.336  4719  4719 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-07 15:41:00.336  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:41:00.336  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:41:00.346  4719  4719 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:śr., 7 gru 15:41
12-07 15:41:00.346  4719  4719 I AODService.ClockTimer: startAlarm : TICK
,12-07 15:41:00.346  3463  4990 V AlarmManager: Add whitelist package alarm :PendingIntent{8600d2: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
12-07 15:41:00.346  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:41:00.356  4719  4719 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
12-07 15:41:00.356  4719  4719 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-07 15:41:00.356  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:41:00.356  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:41:00.356  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:41:00.356  3463  4431 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-07 15:41:00.356  3463  4431 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-07 15:41:00.356  3169  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-07 15:41:00.356  3463  3823 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-07 15:41:00.356  3463  3822 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 41, 0,
12-07 15:41:00.356  3463  4432 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:41:00.356  3463  3822 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 41, 0
,12-07 15:41:00.356  3169  3169 D Sensorhubs: sendContextData: -63, 14, 14, 41, 0
,12-07 15:41:00.366  4719  4719 D DefaultClockView: RootView invalidate()
,12-07 15:41:00.366  3463  3822 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
12-07 15:41:00.366  3463  3822 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
,12-07 15:41:00.366  3463  3822 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
12-07 15:41:00.366  3463  3822 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-07 15:41:00.366  3463  3822 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
12-07 15:41:00.366  3463  3825 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-07 15:41:00.366  3463  4989 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:41:00.366  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:41:00.376  4719  4719 I AODService: onSContextChanged: AODScreenShown state is already true
,12-07 15:41:00.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:00.516  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
,12-07 15:41:00.516  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:41:00.516  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:41:00.516  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:41:00.516  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:41:00.516  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:41:00.516  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
12-07 15:41:00.516  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:41:00.516  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:41:00.516  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:41:00.516  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:41:00.516  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,12-07 15:41:00.516  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:41:00.516  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:41:00.546  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:41:00.546  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:41:00.546  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:41:00.546  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:41:00.546  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:41:00.546  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:41:00.546  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:41:00.546  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:41:00.546  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:41:00.546  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:41:00.546  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:41:00.546  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:41:00.546  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:41:00.566  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:41:00.566  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:41:00.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:00.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:00.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:01.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:01.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:01.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:01.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:01.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:02.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:02.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:02.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:02.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:02.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:02.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:03.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:03.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:03.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:03.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:03.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:04.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:04.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:04.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:04.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:04.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:04.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:05.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:05.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:05.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:05.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:05.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:05.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:06.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:06.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:06.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:06.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:06.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:07.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:07.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:07.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:07.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:07.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:07.856  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:41:07.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:08.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:08.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:08.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:08.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:08.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:09.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:09.126  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:41:09.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:09.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:09.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:09.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:09.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:10.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:10.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:10.376  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, CUR = 142, LCD = 1
,12-07 15:41:10.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:10.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:10.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:11.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:11.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:11.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:11.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:11.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:11.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:12.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:12.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:12.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:12.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:12.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:13.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:13.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:13.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:13.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:13.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:13.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:14.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:14.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:14.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:14.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:14.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:14.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:15.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:15.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:15.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:15.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:15.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:16.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:16.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:16.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:16.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:16.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:16.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:17.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:17.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:17.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:17.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:17.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:18.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:18.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:18.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:18.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:18.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:18.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:19.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:19.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:19.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:19.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:19.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:20.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:20.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:20.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:20.426  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, CUR = 142, LCD = 1
,12-07 15:41:20.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:20.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:20.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:21.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:21.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:21.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:21.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:21.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:22.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:22.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:22.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:22.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:22.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:22.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:23.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:23.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:23.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:23.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:23.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:23.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:24.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:24.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:24.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:24.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:24.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:25.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:25.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:25.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:25.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:25.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:25.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:26.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:26.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:26.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:26.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:26.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:27.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:27.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:27.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:27.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:27.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:27.856  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:41:27.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:28.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:28.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:28.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:28.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:28.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:29.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:29.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:29.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:29.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:29.686  3463  4152 E Watchdog: !@Sync 8 [12-07 15:41:29.690]
,12-07 15:41:29.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:29.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:30.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:30.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:30.346  3463  3857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:41:30.346  3463  3857 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:41:30.346  3463  3857 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-07 15:41:30.346  3463  3857 D BatteryService: stay LED for fully charged
12-07 15:41:30.346  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:41:30.346  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:41:30.346  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:41:30.346  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:41:30.346  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:41:30.356  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:41:30.356  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:41:30.356  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
12-07 15:41:30.366  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:41:30.376  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:41:30.386  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:41:30.386  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:41:30.396  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:41:30.396  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:41:30.396  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:41:30.396  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:41:30.436  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, CUR = 9, LCD = 1
,12-07 15:41:30.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:30.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:30.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:31.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:31.166  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-07 15:41:31.166  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-07 15:41:31.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:31.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:31.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:31.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:31.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:32.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:32.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:32.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:32.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:32.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:32.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:33.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:33.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:33.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:33.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:33.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:34.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:34.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:34.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:34.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:34.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:34.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:35.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:35.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:35.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:35.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:35.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:36.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:36.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:36.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:36.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:36.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:36.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:37.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:37.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:37.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:37.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:37.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:38.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:38.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:38.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:38.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:38.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:38.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:39.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:39.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:39.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:39.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:39.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:40.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:40.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:40.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:40.486  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, CUR = 9, LCD = 1
,12-07 15:41:40.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:40.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:40.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:41.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:41.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:41.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:41.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:41.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:41.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:42.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:42.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:42.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:42.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:42.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:43.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:43.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:43.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:43.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:43.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:43.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:44.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:44.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:44.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:44.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:44.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:45.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:45.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:45.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:45.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:45.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:45.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:46.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:46.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:46.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:46.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:46.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:47.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:47.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:47.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:47.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:47.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:47.856  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:41:47.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:48.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:48.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:48.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:48.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:48.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:49.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:49.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:49.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:49.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:49.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:49.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:50.076  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:41:50.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:50.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:50.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:50.536  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, CUR = 9, LCD = 1
,12-07 15:41:50.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:50.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:50.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:51.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:51.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:51.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:51.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:51.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:52.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:52.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:52.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:52.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:52.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:52.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:53.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:53.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:53.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:53.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:53.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:54.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:54.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:54.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:54.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:54.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:54.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:55.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:55.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:55.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:55.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:55.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:56.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:56.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:56.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:56.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:56.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:56.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:57.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:57.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:57.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:57.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:57.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:58.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:58.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:58.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:58.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:58.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:58.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.686  3463  4152 E Watchdog: !@Sync 9 [12-07 15:41:59.692]
,12-07 15:41:59.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:41:59.996  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:42:00.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:00.346  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:42:00.346  3463  3820 V AlarmManager: Send whitelist package alarm :PendingIntent{8600d2: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:42:00.346  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-07 15:42:00.346  3952  3952 D KeyguardUpdateMonitor: handleTimeUpdate
,12-07 15:42:00.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:00.376  3952  3952 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-07 15:42:00.406  3463  4063 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:42:00.406  3463  4063 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:42:00.406  3463  4063 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-07 15:42:00.406  3463  4063 D BatteryService: stay LED for fully charged
12-07 15:42:00.406  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:42:00.416  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:42:00.416  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:42:00.416  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:42:00.416  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:42:00.416  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:42:00.426  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:42:00.426  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:42:00.426  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:42:00.426  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:42:00.426  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:42:00.426  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:42:00.436  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:42:00.436  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-07 15:42:00.436  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:42:00.436  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:42:00.456  3952  3952 D DateView: received broadcast android.intent.action.TIME_TICK
,12-07 15:42:00.486  8014  8014 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-07 15:42:00.486  8014  8014 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-07 15:42:00.496  4719  4719 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-07 15:42:00.496  4719  4719 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-07 15:42:00.506  3463  3857 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:42:00.506  3463  3857 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-07 15:42:00.506  3463  3857 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-07 15:42:00.506  3463  3857 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,12-07 15:42:00.506  3169  3213 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-07 15:42:00.516  3463  3857 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-07 15:42:00.516  3463  3857 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-07 15:42:00.516  3463  3857 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-07 15:42:00.516  4719  4719 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e89b19, service=Device Physical Context Monitor
12-07 15:42:00.516  4719  4719 I AlpmModeManager: startAlpmMode : state  = BLANK
12-07 15:42:00.516  4719  4719 D DefaultClockView: Window showed. Time views updating
,12-07 15:42:00.516  3463  4063 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:42:00.516  3463  4063 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:42:00.516  3463  4063 D PowerManagerService: mDisplayReady: false
,12-07 15:42:00.516  3463  4063 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:42:00.516  3463  4063 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-07 15:42:00.516  4719  4719 D AODUpdatePositionController: updatePosition: direction[4] updatePosition: X[1] Y[395] NewPositionTimer[55]
12-07 15:42:00.516  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:42:00.516  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:42:00.516  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:42:00.516  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-07 15:42:00.516  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-07 15:42:00.516  4719  4719 D DefaultClockView: LocalTime Pattern : HH:mm
12-07 15:42:00.516  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:42:00.516  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-07 15:42:00.526  4719  4719 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 15:42 time02: null ampm: null
12-07 15:42:00.516  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:42:00.516  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:42:00.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:00.536  3169  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
12-07 15:42:00.536  3463  3823 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-07 15:42:00.536  3463  3822 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 42, 0,
12-07 15:42:00.536  3463  3822 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 42, 0
,12-07 15:42:00.536  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:42:00.536  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:42:00.536  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
,12-07 15:42:00.536  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:42:00.536  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:42:00.536  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:42:00.536  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:42:00.536  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:42:00.536  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:42:00.536  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:42:00.536  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-07 15:42:00.536  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:42:00.536  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:42:00.536  3169  7762 D Sensorhubs: sendContextData: -63, 14, 14, 42, 0
,12-07 15:42:00.546  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:42:00.546  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:42:00.546  3463  3822 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-07 15:42:00.546  3463  3822 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-07 15:42:00.546  3463  3822 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-07 15:42:00.546  3463  3822 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-07 15:42:00.546  3463  3822 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
12-07 15:42:00.546  3463  3825 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-07 15:42:00.546  4719  4719 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
12-07 15:42:00.556  4719  4719 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-07 15:42:00.556  4719  4719 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:śr., 7 gru 15:42
,12-07 15:42:00.556  4719  4719 I AODService.ClockTimer: startAlarm : TICK
,12-07 15:42:00.556  3463  4990 V AlarmManager: Add whitelist package alarm :PendingIntent{4e6f459: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
12-07 15:42:00.556  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, LCD = 1
,12-07 15:42:00.566  4719  4719 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-07 15:42:00.566  4719  4719 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-07 15:42:00.566  3463  4432 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-07 15:42:00.566  3463  4432 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-07 15:42:00.566  4719  4719 I AODService: onSContextChanged: AODScreenShown state is already true
,12-07 15:42:00.566  4719  4719 D DefaultClockView: RootView invalidate()
12-07 15:42:00.566  3463  4413 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:42:00.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:00.716  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
,12-07 15:42:00.716  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:42:00.716  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:42:00.716  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:42:00.716  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:42:00.716  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:42:00.716  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:42:00.716  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:42:00.716  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
,12-07 15:42:00.716  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:42:00.716  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
12-07 15:42:00.716  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-07 15:42:00.726  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-07 15:42:00.726  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:42:00.756  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:42:00.756  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:42:00.756  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:42:00.756  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:42:00.756  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:42:00.756  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:42:00.756  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:42:00.756  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:42:00.756  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:42:00.756  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:42:00.756  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-07 15:42:00.756  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:42:00.756  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:42:00.766  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:42:00.766  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:42:00.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:01.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:01.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:01.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:01.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:01.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:01.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:02.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:02.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:02.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:02.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:02.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:03.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:03.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:03.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:03.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:03.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:03.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:04.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:04.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:04.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:04.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:04.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:05.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:05.126  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:42:05.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:05.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:05.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:05.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:05.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:06.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:06.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:06.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:06.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:06.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:07.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:07.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:07.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:07.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:07.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:07.866  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:42:07.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:08.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:08.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:08.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:08.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:08.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:08.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:09.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:09.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:09.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:09.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:09.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:10.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:10.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:10.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:10.606  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, LCD = 1
,12-07 15:42:10.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:10.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:10.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:11.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:11.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:11.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:11.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:11.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:12.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:12.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:12.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:12.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:12.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:12.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:13.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:13.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:13.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:13.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:13.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:14.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:14.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:14.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:14.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:14.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:14.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:15.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:15.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:15.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:15.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:15.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:16.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:16.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:16.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:16.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:16.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:16.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:17.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:17.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:17.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:17.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:17.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:17.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:18.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:18.356  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:18.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:18.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:18.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:19.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:19.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:19.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:19.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:19.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:19.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:20.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:20.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:20.516  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:20.656  3463  6435 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:14), CP = 247, LCD = 1
,12-07 15:42:20.696  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:20.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:21.056  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:21.236  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:21.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:21.596  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:21.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:21.956  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:22.136  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:22.316  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:22.496  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:22.676  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:22.856  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:23.036  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:23.216  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:23.396  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:23.576  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:23.756  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:23.936  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:24.116  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:24.296  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:24.476  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:24.656  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:24.836  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:25.016  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:25.196  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:25.376  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:25.556  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:25.736  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:25.916  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:26.096  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:26.276  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:26.456  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:26.636  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:26.816  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:26.996  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:27.176  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:27.226  3463  3812 D TimaService: TIMA: TimaService scheduler is intialized. 
12-07 15:42:27.226  3463  3812 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,12-07 15:42:27.226  3463  3811 D TimaService: TimaServiceHandler.handleMessage what =1
,12-07 15:42:27.236  3463  3812 I TLC_TIMA_PKM_initialize: initializing...
12-07 15:42:27.236  3463  3812 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
12-07 15:42:27.236  3463  3812 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: device_id = 0x0
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: tlc_open() was called
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: Opening MobiCore device
12-07 15:42:27.236  3463  3812 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,12-07 15:42:27.236  3463  3812 I TZ: mc_tlc_communication: Opening the session
,12-07 15:42:27.286  3463  3812 I TZ: mc_tlc_communication: tlc_open() succeeded
12-07 15:42:27.286  3463  3812 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,12-07 15:42:27.296  3463  3812 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,12-07 15:42:27.306  3463  3812 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,12-07 15:42:27.336  3463  3812 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,12-07 15:42:27.336  3463  3812 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,12-07 15:42:27.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:27.536  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:27.716  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:27.866  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:42:27.896  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:28.076  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:28.256  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:28.436  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:28.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:28.796  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:28.976  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:29.156  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:29.336  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:29.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:29.686  3463  4152 E Watchdog: !@Sync 10 [12-07 15:42:29.694]
12-07 15:42:29.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:29.876  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.416  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.466  3463  3857 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-07 15:42:30.466  3463  3857 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:42:30.466  3463  3857 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-07 15:42:30.466  3463  3857 D BatteryService: stay LED for fully charged
12-07 15:42:30.466  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:42:30.476  3463  3463 I MotionRecognitionService: Plugged
,12-07 15:42:30.476  3463  3463 D MotionRecognitionService:   cableConnection= 1
12-07 15:42:30.476  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:42:30.476  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:42:30.486  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:42:30.486  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-07 15:42:30.486  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-07 15:42:30.486  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:42:30.506  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:42:30.516  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-07 15:42:30.516  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:42:30.516  5067  5067 D BatteryMonitor: new battery level: 100
,12-07 15:42:30.516  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:42:30.536  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-07 15:42:30.536  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:42:30.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.676  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 289 (W:10), CP = 247, LCD = 1
,12-07 15:42:30.776  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:30.986  3463  3812 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
12-07 15:42:30.986  3463  3812 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,12-07 15:42:30.996  3463  3812 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-07 15:42:30.996  3463  3812 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-07 15:42:31.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:31.266  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-07 15:42:31.266  4399  4467 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-07 15:42:31.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:31.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:31.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:31.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:32.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:32.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:32.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:32.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:32.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:32.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:33.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:33.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:33.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:33.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:33.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:34.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:34.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:34.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:34.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:34.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:34.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:35.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:35.156  3154  3636 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-07 15:42:35.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:35.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:35.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:35.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:35.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:36.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:36.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:36.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:36.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:36.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:37.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:37.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:37.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:37.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:37.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:37.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:38.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:38.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:38.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:38.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:38.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:39.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:39.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:39.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:39.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:39.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:39.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:40.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:40.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:40.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:40.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:40.726  3463  6435 D SSRM:n  : SIOP:: AP = 290, PST = 289 (W:10), CP = 247, LCD = 1
,12-07 15:42:40.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:41.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:41.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:41.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:41.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:41.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:41.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:42.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:42.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:42.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:42.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:42.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:43.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:43.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:43.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:43.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:43.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:43.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:44.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:44.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:44.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:44.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:44.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:44.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:45.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:45.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:45.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:45.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:45.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:46.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:46.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:46.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:46.616  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:46.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:46.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:47.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:47.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:47.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:47.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:47.866  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:42:47.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:48.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:48.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:48.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:48.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:48.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:48.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:49.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:49.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:49.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:49.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:49.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:50.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:50.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:50.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:50.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:50.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:50.766  3463  6435 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:10), CP = 247, LCD = 1
,12-07 15:42:50.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:51.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:51.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:51.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:51.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:51.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:52.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:52.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:52.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:52.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:52.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:52.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:53.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:53.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:53.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:53.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:53.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:53.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:54.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:54.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:54.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:54.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:54.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:55.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:55.216  8987  9028 W PlayEventLogger: No account for auth token provided
,12-07 15:42:55.236  8987  9028 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-07 15:42:55.236  8987  9028 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-07 15:42:55.246  3154  3640 D EnterpriseController: netId is 0
,12-07 15:42:55.246  3154  3640 D Netd    : getNetworkForDns: using netid 502 for uid 10035
12-07 15:42:55.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:55.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:55.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:55.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:55.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:56.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:56.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:56.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:56.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:56.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:57.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:57.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:57.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:57.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:57.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:57.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:58.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:58.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:58.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:58.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:58.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.686  3463  4152 E Watchdog: !@Sync 11 [12-07 15:42:59.695]
,12-07 15:42:59.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:42:59.996  3463  3820 V AlarmManager: Expired Alarm result :8
,12-07 15:43:00.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:00.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:00.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:00.516  3463  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-07 15:43:00.516  3463  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-07 15:43:00.516  3463  4339 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-07 15:43:00.526  3463  4339 D BatteryService: stay LED for fully charged
12-07 15:43:00.526  3463  3463 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-07 15:43:00.526  3463  3463 I MotionRecognitionService: Plugged
12-07 15:43:00.526  3463  3463 D MotionRecognitionService:   cableConnection= 1
,12-07 15:43:00.526  3463  3463 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-07 15:43:00.526  3463  3463 D MotionRecognitionService: skip setTransmitPower. 
,12-07 15:43:00.536  3463  3866 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-07 15:43:00.536  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-07 15:43:00.536  3952  3952 D KeyguardUpdateMonitor: handleBatteryUpdate
12-07 15:43:00.536  3952  3952 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-07 15:43:00.556  3463  3820 V AlarmManager: Expired Alarm result :4
,12-07 15:43:00.566  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,12-07 15:43:00.576  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-07 15:43:00.576  5027  5420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-07 15:43:00.586  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:43:00.586  3952  3952 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-07 15:43:00.586  5067  5067 D BatteryMonitor: new battery level: 100
12-07 15:43:00.586  4719  4719 D BatteryController: saveBatteryData : level[100], status[5]
,12-07 15:43:00.596  3463  3820 V AlarmManager: Send whitelist package alarm :PendingIntent{4e6f459: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:43:00.596  3952  3952 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-07 15:43:00.596  3952  3952 D KeyguardUpdateMonitor: handleTimeUpdate
,12-07 15:43:00.606  3952  3952 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-07 15:43:00.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:00.666  3952  3952 D DateView: received broadcast android.intent.action.TIME_TICK
,12-07 15:43:00.706  8014  8014 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-07 15:43:00.706  8014  8014 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-07 15:43:00.716  4719  4719 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-07 15:43:00.716  4719  4719 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-07 15:43:00.726  3463  4432 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:43:00.726  3463  4432 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-07 15:43:00.726  3463  4432 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-07 15:43:00.726  3463  4432 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-07 15:43:00.726  3169  3169 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-07 15:43:00.736  3463  4432 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-07 15:43:00.736  3463  4432 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-07 15:43:00.736  3463  4432 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-07 15:43:00.736  4719  4719 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e89b19, service=Device Physical Context Monitor
12-07 15:43:00.736  4719  4719 I AlpmModeManager: startAlpmMode : state  = BLANK
12-07 15:43:00.736  4719  4719 D DefaultClockView: Window showed. Time views updating
,12-07 15:43:00.736  3463  4339 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
12-07 15:43:00.736  3463  4339 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:43:00.736  3463  4339 D PowerManagerService: mDisplayReady: false
12-07 15:43:00.736  3463  4339 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-07 15:43:00.736  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:43:00.736  4719  4719 D AODUpdatePositionController: updatePosition: direction[1] updatePosition: X[0] Y[394] NewPositionTimer[54]
12-07 15:43:00.736  3463  4339 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:43:00.736  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:43:00.736  4719  4719 D DefaultClockView: LocalTime Pattern : HH:mm
12-07 15:43:00.736  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:43:00.736  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:43:00.736  3463  3591 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,12-07 15:43:00.736  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-07 15:43:00.736  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-07 15:43:00.746  4719  4719 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 15:43 time02: null ampm: null
,12-07 15:43:00.746  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb5703c00
12-07 15:43:00.746  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-07 15:43:00.756  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-07 15:43:00.756  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:43:00.756  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:43:00.756  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:43:00.756  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:43:00.756  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:43:00.756  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-07 15:43:00.756  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-07 15:43:00.756  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:43:00.756  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:43:00.756  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:43:00.756  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:43:00.756  6182  6182 E CocktailBarPositionManager: Window direction: 0
,12-07 15:43:00.756  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
12-07 15:43:00.756  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:43:00.766  3169  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,12-07 15:43:00.766  4719  4719 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
12-07 15:43:00.766  3463  3823 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
12-07 15:43:00.766  4719  4719 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-07 15:43:00.766  3463  3822 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 43, 0,
12-07 15:43:00.766  3463  3822 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 43, 0
12-07 15:43:00.766  4719  4719 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:śr., 7 gru 15:43
12-07 15:43:00.766  4719  4719 I AODService.ClockTimer: startAlarm : TICK
12-07 15:43:00.766  3169  3213 D Sensorhubs: sendContextData: -63, 14, 14, 43, 0
,12-07 15:43:00.766  3463  4062 V AlarmManager: Add whitelist package alarm :PendingIntent{93546cc: PendingIntentRecord{37ae4ec com.samsung.android.app.aodservice broadcastIntent}}
,12-07 15:43:00.766  4719  4719 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-07 15:43:00.766  4719  4719 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-07 15:43:00.766  3463  4326 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-07 15:43:00.766  3463  4326 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-07 15:43:00.776  3463  3492 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:43:00.776  4719  4719 D DefaultClockView: RootView invalidate()
,12-07 15:43:00.776  3463  3822 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-07 15:43:00.776  3463  3822 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-07 15:43:00.776  3463  4413 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463
,12-07 15:43:00.776  3463  3822 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
12-07 15:43:00.776  3463  3822 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,12-07 15:43:00.786  3463  6435 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:10), CP = 247, LCD = 1
12-07 15:43:00.776  3463  3822 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
12-07 15:43:00.776  3463  3825 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-07 15:43:00.796  4719  4719 I AODService: onSContextChanged: AODScreenShown state is already true
,12-07 15:43:00.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:00.936  3463  3463 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3463 (0x0)
,12-07 15:43:00.936  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable
12-07 15:43:00.936  3463  3463 D PowerManagerService: mDisplayReady: false
12-07 15:43:00.936  3463  3463 I libsuspend: !@autosuspend_wakeup_count_disable done
12-07 15:43:00.936  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-07 15:43:00.936  3463  3463 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-07 15:43:00.936  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb5703c00
12-07 15:43:00.936  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:43:00.936  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-07 15:43:00.936  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:43:00.936  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-07 15:43:00.936  3463  3591 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-07 15:43:00.936  3463  3578 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-07 15:43:00.936  3463  3578 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-07 15:43:00.966  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:43:00.966  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:43:00.966  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable
12-07 15:43:00.966  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:43:00.966  3463  3582 I libsuspend: !@autosuspend_wakeup_count_enable done
12-07 15:43:00.966  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:43:00.966  3463  3582 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-07 15:43:00.966  3463  3582 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-07 15:43:00.966  3463  3582 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-07 15:43:00.966  3463  3582 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-07 15:43:00.966  3463  3582 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-07 15:43:00.966  3463  3582 D PowerManagerService: mDisplayReady: true
12-07 15:43:00.966  3463  3582 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-07 15:43:00.986  6182  6182 E CocktailBarPositionManager: Window direction: 0
12-07 15:43:00.986  6182  6182 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-07 15:43:01.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:01.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:01.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:01.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:01.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:01.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:02.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:02.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:02.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:02.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:02.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:02.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:03.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:03.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:03.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:03.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:03.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:04.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:04.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:04.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:04.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:04.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:04.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:05.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:05.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:05.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:05.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:05.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:06.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:06.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:06.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:06.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:06.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:06.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:07.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:07.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:07.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:07.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:07.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:07.866  3463  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-07 15:43:08.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:08.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:08.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:08.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:08.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:08.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:09.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:09.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:09.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:09.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:09.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:10.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:10.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:10.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:10.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:10.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:10.826  3463  6435 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:14), CP = 247, LCD = 1
,12-07 15:43:10.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:11.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:11.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:11.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:11.626  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:11.806  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:11.986  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:12.166  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:12.346  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:12.526  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:12.706  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:12.886  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:13.066  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:13.246  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:13.426  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:13.606  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:13.786  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:13.966  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:14.146  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:14.326  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:14.506  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:14.686  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:14.866  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:15.046  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:15.226  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:15.406  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:15.586  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:15.766  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:15.946  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:16.126  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:16.306  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:16.486  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:16.666  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:16.846  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:17.026  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:17.206  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:17.386  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:17.566  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:17.746  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:17.926  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:18.106  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:18.286  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:18.466  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:18.646  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:18.826  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:19.006  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:19.186  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:19.366  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:19.546  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:19.726  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:19.906  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:20.086  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:20.266  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,12-07 15:43:20.446  3463  3800 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
