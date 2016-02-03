#### Test 58135655e794d2c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
W/ResourcesManager( 2643): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
--------- beginning of main
V/SmartcardService( 2643): main Received broadcast
V/SmartcardService( 2643): Starting smartcard service after boot completed
I/iu.UploadsManager( 1770): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
I/ActivityManager(  822): Start proc 2671:org.simalliance.openmobileapi.service:remote/u0a23 for service org.simalliance.openmobileapi.service/.SmartcardService
I/BooksSync( 2567): Starting books sync for 61035162, extras: ade
I/ActivityManager(  822): Start proc 2692:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
W/ResourcesManager( 2671): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
I/iu.UploadsManager( 1770): End new media; added: 0, uploading: 0, time: 133 ms
V/SmartcardService( 2671): main smartcard service onCreate
V/SmartcardService( 2671): main adding SIM - UICC
V/MediaScanner( 1087): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@20b0f70e
V/MediaScanner( 1087): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@20b0f70e
I/SmartcardService( 2671): Initializing Access Control
I/SmartcardService( 2671): NOT initializing Access Control for SIM - UICC SE not present.
I/SmartcardService( 2671): OnPostExecute()
V/SmartcardService( 2671): register SIM_STATE_CHANGED event
V/SmartcardService( 2671): register ADAPTER_STATE_CHANGED event
V/SmartcardService( 2671): register MEDIA_MOUNTED event
E/UpdateRequestReceiver( 2692): ignoring update request
E/UpdateRequestReceiver( 2692): ignoring update request
I/BooksConfig( 2567): GmsCore Version = 7.8.99 (2134222-430)
E/UpdateRequestReceiver( 2692): ignoring update request
E/UpdateRequestReceiver( 2692): ignoring update request
E/UpdateRequestReceiver( 2692): ignoring update request
E/UpdateRequestReceiver( 2692): ignoring update request
I/ActivityManager(  822): Killing 2285:com.google.android.apps.photos/u0a71 (adj 15): empty #17
I/GoogleHttpClient( 1259): GMS http client unavailable, use old client
I/ActivityManager(  822): Start proc 2730:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
I/ActivityManager(  822): Start proc 2747:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/BooksAccountManager( 2567): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2567): Soft error
E/BooksSync( 2567): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2567): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 2567): Sync error
E/BooksSync( 2567): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2567): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 2567): Finished books sync
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39552, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  822): Killing 2344:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/ContactLocale( 2747): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  822): Killing 1844:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
I/ActivityManager(  822): Killing 2365:com.google.android.deskclock/u0a44 (adj 15): empty #17
D/StrictMode( 2730): StrictMode policy violation; ~duration=589 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 2730): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 2730): 	at java.io.File.exists(File.java:363)
D/StrictMode( 2730): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 2730): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 2730): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 2730): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 2730): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=588 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 2730): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 2730): 	at java.io.File.exists(File.java:363)
D/StrictMode( 2730): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=585 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 2730): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 2730): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 2730): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 2730): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 2730): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 2730): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 2730): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=579 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 2730): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 2730): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=560 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 2730): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 2730): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 2730): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 2730): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 2730): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=451 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 2730): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 2730): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 2730): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 2730): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 2730): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 2730): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 2730): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 2730): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 2730): # via Binder call with stack:
D/StrictMode( 2730): android.os.StrictMode$LogStackTrace
D/StrictMode( 2730): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 2730): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 2730): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 2730): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 2730): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 2730): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 2730): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 2730): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 2730): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 2730): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 2730): 	at java.io.File.exists(File.java:363)
D/StrictMode( 2730): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 2730): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 2730): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 2730): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 2730): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 2730): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 2730): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 2730): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 2730): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 2730): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 2730): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 2730): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 2730): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 2730): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 2730): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 2730): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 2730): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 2730): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 2730): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 2730): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 2730): 	at com.google.p.j.a(PG:121)
D/StrictMode( 2730): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 2730): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 2730): 	at com.google.p.e.a(PG:170)
D/StrictMode( 2730): 	at com.google.p.e.b(PG:21)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 2730): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 2730): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 2730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 2730): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 2730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 2730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 2730): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 2730): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 2730): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 2730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/ActivityThread( 2730): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/com.google.a.a.a.b.a( 2730): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  822): Message: 20
,I/GAv4-SVC( 1770): Google Analytics 7.8.99 is starting up.
I/GAV2    ( 2302): Thread[GAThread,5,main]: No campaign data found.
I/art     (  822): Explicit concurrent mark sweep GC freed 15264(703KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.473ms total 81.532ms
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dfeea64:true
I/ActivityManager(  822): Start proc 2783:com.qualcomm.telephony/1000 for broadcast com.qualcomm.atfwd/.AtFwdAutoboot
I/ActivityManager(  822): Killing 2409:com.android.keychain/1000 (adj 15): empty #17
D/AndroidRuntime( 2790): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
W/ContextImpl( 2783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2609 
D/AndroidRuntime( 2790): CheckJNI is OFF
E/AtFwd AutoBoot( 2783): AtFwd Auto Boot Started Successfully
D/AtFwdService( 2783): onCreate method
I/AtFwdService( 2783): Instantiate AtCmdFwd Service
D/AtCkpdCmdHandler( 2783): De-queing command
I/ActivityManager(  822): Start proc 2809:com.qualcomm.telephony/1001 for broadcast org.codeaurora.ims/.ImsServiceAutoboot
D/AndroidRuntime( 2790): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{17469eda token=Token{36b07085 ActivityRecord{3d7b21fc u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 2790): Shutting down VM
I/HotwordDetector( 1526): Closing mic
I/MicrophoneInputStream( 1526): mic_close com.google.android.apps.gsa.speech.audio.u@2fcbf9f
V/WindowManager(  822): Adding window Window{1723b494 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1bb16337 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
E/ImsService AutoBoot( 2809): ImsService Auto Boot Started Successfully
D/ImsService( 1367): ImsService created!
D/ImsSenderRxr( 1367): Starting IFMsg_Rxr
D/ImsSenderRxr( 1367): Connecting to socket android.net.LocalSocket@2c632864 impl:android.net.LocalSocketImpl@3ddedacd fd:FileDescriptor[65]
I/ImsSenderRxr( 1367): Connected to 'android.net.LocalSocket@2c632864 impl:android.net.LocalSocketImpl@3ddedacd fd:FileDescriptor[65]' socket
V/ImsSenderRxr( 1367): Read packet: 15 bytes
V/ImsSenderRxr( 1367): processResponse
D/ImsSenderRxr( 1367): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsConfigImpl( 1367): ImsConfigImpl Creates
D/ImsSenderRxr( 1367):  Tag -1 3 213 0
I/ActivityManager(  822): Start proc 2840:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/ActivityManager(  822): Killing 2431:com.google.android.dialer/u0a13 (adj 15): empty #17
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1526): Hotword detection finished
I/HotwordRecognitionRnr( 1526): Stopping hotword detection.
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 523us total 29.385ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 317us total 12.932ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 322us total 13.360ms
D/ImsConfigImpl( 1367): mcc = 0, mnc = 0
D/ImsSenderRxr( 1367): [0000]> REQUEST_QUERY_SERVICE_STATUS
D/ImsSenderRxr( 1367): Message data: [0, 0, 0, 12, 11, 13, 0, 0, 0, 0, 16, 1, 24, 29, 32, 0]
V/ImsSenderRxr( 1367): Read packet: 12 bytes
V/ImsSenderRxr( 1367): processResponse
D/ImsSenderRxr( 1367): Response data: [11, 13, 0, 0, 0, 0, 16, 2, 24, 29, 32, 2]
D/ImsSenderRxr( 1367):  Tag 0 2 29 2
D/ImsSenderRxr( 1367): [0000]< REQUEST_QUERY_SERVICE_STATUS error: 2
,D/ImsServiceSub( 1367): Message received: what = 5
D/ImsServiceSub( 1367): Received event: EVENT_GET_STATUS_UPDATE
E/ImsServiceSub( 1367): IMS Service Status Update failed!
,V/GLSUser ( 1259): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,V/GmsCoreStatsServiceLauncher( 1770): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ImsServiceClassTracker( 1367): updateVtCapability false
D/ImsServiceSub( 1367): send new listener registered event
D/ImsServiceSub( 1367): getServiceId returns 1
D/ImsSenderRxr( 1367): [0001]> REQUEST_IMS_REGISTRATION_STATE
D/ImsSenderRxr( 1367): Message data: [0, 0, 0, 12, 11, 13, 1, 0, 0, 0, 16, 1, 24, 1, 32, 0]
D/ImsServiceSub( 1367): Message received: what = 12
,D/ImsService( 1367): Open returns serviceId 1
,V/ImsSenderRxr( 1367): Read packet: 12 bytes
V/ImsSenderRxr( 1367): processResponse
,D/ImsSenderRxr( 1367): Response data: [11, 13, 1, 0, 0, 0, 16, 2, 24, 1, 32, 2]
D/ImsSenderRxr( 1367):  Tag 1 2 1 2
D/ImsSenderRxr( 1367): [0001]< REQUEST_IMS_REGISTRATION_STATE error: 2
,D/ImsServiceSub( 1367): Message received: what = 3,
,E/ImsServiceSub( 1367): IMS State query failed!
D/ImsSenderRxr( 1367): setUiTTYMode uittyMode=0,
,D/ImsSenderRxr( 1367): [0002]> REQUEST_SEND_UI_TTY_MODE
D/ImsSenderRxr( 1367): Message data: [0, 0, 0, 14, 11, 13, 2, 0, 0, 0, 16, 1, 24, 39, 32, 0, 8, 0]
,D/PersistentNotificationBroadcastReceiver( 1259): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/WebViewFactory( 2840): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2840): Time to load native libraries: 8 ms (timestamps 2677-2685)
,I/LibraryLoader( 2840): Expected native library version number "",actual native library version number ""
,W/InstanceID/Rpc( 1770): Found 10011
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1722115347
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/ImsSenderRxr( 1367): Read packet: 12 bytes
V/ImsSenderRxr( 1367): processResponse
D/ImsSenderRxr( 1367): Response data: [11, 13, 2, 0, 0, 0, 16, 2, 24, 39, 32, 0]
D/ImsSenderRxr( 1367):  Tag 2 2 39 0
D/ImsSenderRxr( 1367): [0002]< REQUEST_SEND_UI_TTY_MODE 
,V/WebViewChromiumFactoryProvider( 2840): Binding Chromium to main looper Looper (main, tid 1) {14bdfd61}
,I/LibraryLoader( 2840): Expected native library version number "",actual native library version number ""
I/chromium( 2840): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  822): Killing 2482:com.motorola.motocit/u0a2 (adj 15): empty #17
,I/BrowserStartupController( 2840): Initializing chromium process, singleProcess=true
,W/art     ( 2840): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2840): ApplicationContext is null in ApplicationStatus
,W/chromium( 2840): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2840): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2840): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 2840): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7be9473:true
,D/FileApkUtils( 1770): Spent 19ms computing apk sha1.
,D/FileApkUtils( 1770): Module already staged or being staged:chimera-modules/MapsModule.apk
,W/art     ( 2840): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2840): onDetachedFromWindow called when already detached. Ignoring
,D/GCM     ( 1770): COMPAT: Multi user ser=0 current=0
,D/DexOptUtils( 1770): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d27787c4e483aadd035a354447c9e84728eb2ab4/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1770): Keeping up-to-date module: module-d27787c4e483aadd035a354447c9e84728eb2ab4
,D/GCM     ( 1259): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/SystemWebViewEngine( 2840): CordovaWebView is running on device made by: motorola
,D/GmsModuleFndr( 1770): Beginning GMS chimera module scan
,W/art     ( 2840): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2840): Attempt to remove local handle scope entry from IRT, ignoring
I/CheckinService( 1770): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ConfigService( 1259): onCreate
I/ConfigFetchService( 1770): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,D/GmsModuleFndr( 1770): Module pkg com.google.android.apps.kids.familylink not installed, skipping
D/ChimeraCfgMgr( 1770): Beginning module configuration check
,I/GCoreUlr( 1770): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ChimeraCfgMgr( 1770): Module APKs unchanged, check complete
I/SystemUpdateService( 1770): showing system update notification
,V/AuthZen ( 1770): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1770): Handling event: android.intent.action.BOOT_COMPLETED
D/OpenGLRenderer( 2840): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 2840): Validating map...
V/WindowManager(  822): Adding window Window{d6a1554 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1723b494 u0 Starting com.test.thalitest})
,I/GCoreUlr( 1808): DispatchingService.onCreate()
,W/chromium( 2840): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/CheckinService( 1770): Checking schedule, now: 1454534043083 next: 1454558123594
I/CheckinService( 1770): active receiver: disabled
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,I/ValidateNoPeople(  822): skipping global notification
,I/OpenGLRenderer( 2840): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2840): Enabling debug mode 0
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599909 ms
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 11253(657KB) AllocSpace objects, 5(174KB) LOS objects, 37% free, 26MB/42MB, paused 1.453ms total 30.546ms
,I/art     ( 1770): Explicit concurrent mark sweep GC freed 26829(1799KB) AllocSpace objects, 18(288KB) LOS objects, 36% free, 27MB/43MB, paused 1.672ms total 70.894ms
I/ConfigFetchService( 1770): service connected
,I/AuthZen ( 1770): Fetching signing key...
,I/Keyboard.Facilitator( 1237): onFinishInput()
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +715ms
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
I/AuthZen ( 1770): Signing key fetched successfully!
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,I/art     ( 1808): Explicit concurrent mark sweep GC freed 14009(775KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.721ms total 67.582ms
,W/BindingManager( 2840): Cannot call determinedVisibility() - never saw a connection for the pid: 2840
,I/AuthZen ( 1770): Starting Enrollment...
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35918d97:true
,I/ActivityManager(  822): Start proc 2930:com.google.android.youtube/u0a86 for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,D/SystemUpdateService( 1770): onDestroy
D/AuthZen ( 1770): getting auth token. Attempt 0
,D/ConfigFetchService( 1770): ConfigApi connection successful.
,I/GLSActivity( 1259): [ac] getting account id
,I/GLSUser ( 1259): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GCoreUlr( 1808): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/JsMessageQueue( 2840): Set native->JS mode to OnlineEventsBridgeMode
,E/AuthZen ( 1770): Error getting auth token
E/AuthZen ( 1770): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/AuthZen ( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 1770): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1770): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1770): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/AuthZen ( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 1770): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1770): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1770): Clearing transaction cache
,I/art     (  822): Explicit concurrent mark sweep GC freed 14050(691KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 3.054ms total 62.358ms
,D/jxcore_app_log( 2840): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576398592
,I/GCoreUlr( 1808): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/chromium( 2840): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GCoreUlr( 1808): Unbound from all location providers
,I/GCoreUlr( 1808): DispatchingService.onDestroy()
,I/GCoreUlr( 1808): Unbound from all location providers
,W/ResourcesManager( 2930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2930): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 2930): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 2968): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads363118548.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads363118548.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 2968): dex2oat took 45.189ms (threads: 4) arena alloc=81KB java alloc=12KB native alloc=839KB free=7MB
,E/YouTube MDX( 2930): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/InstanceID/Rpc( 2930): Found 10011
,D/WifiService(  822): New client listening to asynchronous messages
,I/ActivityManager(  822): Killing 1184:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3035:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,W/ResourcesManager( 3035): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1526): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1526): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 1526): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1526): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1526): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1526): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1526): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1526): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,E/VelvetNetworkClient( 1526): Failed to get auth token
,I/Babel_SMS( 3035): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3035): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3035): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3035): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3035): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3035): MmsConfig.loadFromResources
,E/Babel_SMS( 3035): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3035): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3035): startup - clean
,I/Babel   ( 3035): deleted: false for 0
,I/Babel_telephony( 3035): TeleModule.launchCompleted
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3035): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3035): BAM#gBA: invalid account id: -1
W/Babel   ( 3035): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3035): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,W/jxcore-log( 2840): Initializing JXcore engine
W/jxcore-log( 2840): JXcore engine is ready
W/VideoCapabilities( 3035): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3035): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3035): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3035): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3035): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3035): Unrecognized profile 2130706433 for video/avc
,W/Thread-296( 2953): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10471]" dev="sockfs" ino=10471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-296( 2953): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-296( 2953): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10678]" dev="sockfs" ino=10678 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-296( 2953): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[18785]" dev="sockfs" ino=18785 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,I/vclib   ( 3035): onServiceConnected
,W/Babel   ( 3035): Attempted to change video mute state without an active call.
,W/jxcore-log( 2840): Starting JXcore engine
,I/ActivityManager(  822): Start proc 3067:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.FitnessBootReceiver
I/ActivityManager(  822): Killing 2519:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,W/jxcore-log( 2840): Platform android
W/jxcore-log( 2840): 
W/jxcore-log( 2840): Process ARCH arm
W/jxcore-log( 2840): 
,I/FitnessApp( 3067): Initializers took 0 milliseconds
,I/ActivityManager(  822): Start proc 3086:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  822): Killing 2261:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,I/GAv4    ( 3086): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3086):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3086):   adb logcat -s GAv4
,W/GAv4    ( 3086): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3086): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3086): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 2840): JXcore Cordova bridge is ready!
I/jxcore-log( 2840): 
W/jxcore-log( 2840): JXcore engine is started
,I/ActivityManager(  822): Start proc 3108:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
I/ActivityManager(  822): Killing 2593:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,I/GAV2    ( 2567): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 2840): Toggling radios to true
I/jxcore-log( 2840): 
,D/BluetoothAdapter( 2840): enable(): BT is already enabled..!
,D/WifiService(  822): setWifiEnabled: true pid=2840, uid=10265
D/WifiService(  822): New client listening to asynchronous messages
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2840): Radios toggled
I/jxcore-log( 2840): 
I/jxcore-log( 2840): My device name is: motorola-Nexus 6
I/jxcore-log( 2840): 
,I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1259): Read error: ssl=0xaec5a000: I/O error during system call, Connection timed out
V/NativeCrypto( 1259): SSL shutdown failed: ssl=0xaec5a000: I/O error during system call, Broken pipe
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1068): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
D/Tethering(  822): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/PhoneInterfaceManager( 1367): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1367): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1367): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1367): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,D/Finsky  ( 3108): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3108): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 3152:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/ResourcesManager( 3152): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3152): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Settings( 3108): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3108): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/MultiDex( 3152): VM with version 2.1.0 has multidex support
I/MultiDex( 3152): install
I/MultiDex( 3152): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 3108): [313] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3108): [306] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 3152): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  822): Start proc 3172:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/ActivityManager(  822): Killing 2545:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ProviderInstaller( 3152): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 3108): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3108): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 3108): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3108): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  822): Killing 2623:com.android.settings/1000 (adj 15): empty #17
,V/Finsky  ( 3108): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/Gmail   ( 3172): getAccountsCursor
,D/ActivityThread( 3172): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1178): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Start proc 3206:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,I/art     (  822): Explicit concurrent mark sweep GC freed 28262(1408KB) AllocSpace objects, 9(144KB) LOS objects, 32% free, 33MB/49MB, paused 1.482ms total 71.975ms
,W/ActivityManager(  822): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/GAV2    ( 3172): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 3172): Observing account changes for notifications
,I/Exchange( 3206): EasService.onCreate
,I/Exchange( 3206): RestartPingTask
,I/Exchange( 3206): RestartPingsTask did not start any pings.
I/Exchange( 3206): PSS stopIfIdle
I/Exchange( 3206): PSS has no active accounts; stopping service.
,I/Gmail   ( 3172): getAccountsCursor
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemBroadcastReceiver( 1237): Boot has been completed
I/SystemBroadcastReceiver( 1237): toggleAppIcon() : FLAG_SYSTEM = true
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 3206): onDestroy
,I/ActivityManager(  822): Killing 2643:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 9826(539KB) AllocSpace objects, 5(551KB) LOS objects, 38% free, 25MB/41MB, paused 677us total 19.438ms
,I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,I/ActivityManager(  822): Start proc 3244:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
,I/Exchange( 3206): EasService.onCreate
,I/Exchange( 3206): RestartPingTask
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 89
E/WifiStateMachine(  822):  RSSI mgmt: -52
E/WifiStateMachine(  822):  BE :  rx=111 tx=112 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 6972 tx_time=147 rx_time=247 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/Exchange( 3206): RestartPingsTask did not start any pings.
I/Exchange( 3206): PSS stopIfIdle
I/Exchange( 3206): PSS has no active accounts; stopping service.
,I/Exchange( 3206): onDestroy
,E/SQLiteLog( 3172): (283) recovered 62 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/Gmail   ( 3172): notifyAccountChanged
,I/Gmail   ( 3172): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3172): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3172): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,I/Gmail   ( 3172): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3172): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3172): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,I/Gmail   ( 3172): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,I/ActivityManager(  822): Killing 2322:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/dhcpcd  ( 3265): version 5.5.6 starting
,I/dhcpcd  ( 3265): wlan0: rebinding lease of 192.168.1.122
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3172): getAccountsCursor
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3172): getAccountsCursor
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 3244): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3244): Unsupported profile 4 for video/mp4v-es
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,W/ResourcesManager( 3244): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Bugle   ( 3244): ApnsOta: OTA version -1
W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,I/art     ( 3244): Note: end time exceeds epoch: 
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,I/BugleUsageStatistics( 3244): PlayLogger.onLoggerConnected
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,I/BugleDataModel( 3244): Fixup: Send failed - 0 Download failed - 0
,I/ActivityManager(  822): Start proc 3289:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.InternalReceiver
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3244): PhoneUtils.getSelfRawNumber: subInfo is null for -1
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3244): PhoneUtils.getForLMR1(): invalid subId = -1
,I/BugleDataModel( 3244): SyncMessagesAction: Starting batch for messages from 1454531491309 to 1454534048017 (message update limit = 80, message scan limit = 4000)
,I/BugleDataModel( 3244): SyncMessagesAction: All messages now in sync
,I/ActivityManager(  822): Killing 2692:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3315:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 11.160ms
,V/UserPresentBroadcastReceiver( 1808): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/art     (  369): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 10.086ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.222ms
,W/ResourcesManager( 3315): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  822): Start proc 3334:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  822): Killing 2730:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/dhcpcd  ( 3265): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3265): wlan0: leased 192.168.1.122 for 86400 seconds
,I/CalendarProvider2( 3315): Created com.android.providers.calendar.CalendarAlarmManager@1c1da8c8(com.android.providers.calendar.CalendarProvider2@14bdfd61)
,I/ActivityManager(  822): Killing 2567:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3375:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1068): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1367): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1367): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
E/GpsLocationProvider(  822): No APN found to select.
,I/art     (  822): Explicit concurrent mark sweep GC freed 26184(1265KB) AllocSpace objects, 3(140KB) LOS objects, 32% free, 33MB/49MB, paused 1.592ms total 53.717ms
,D/StrictMode( 3375): StrictMode policy violation; ~duration=261 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3375): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3375): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3375): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3375): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3375): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3375): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3375): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=260 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3375): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3375): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3375): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=259 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3375): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3375): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3375): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3375): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3375): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3375): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3375): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=255 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3375): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3375): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=251 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3375): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3375): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3375): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3375): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3375): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3375): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3375): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3375): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3375): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3375): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3375): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3375): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3375): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3375): # via Binder call with stack:
D/StrictMode( 3375): android.os.StrictMode$LogStackTrace
D/StrictMode( 3375): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3375): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3375): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3375): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3375): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3375): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3375): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3375): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3375): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3375): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3375): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3375): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3375): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3375): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3375): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3375): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3375): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3375): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3375): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3375): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3375): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3375): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3375): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3375): StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3375): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3375): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3375): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3375): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3375): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3375): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3375): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3375): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3375): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3375): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3375): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3375): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3375): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3375): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3375): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3375): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/ActivityThread( 3375): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/com.google.a.a.a.b.a( 3375): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@330c65af:true
I/ActivityManager(  822): Killing 1924:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1259): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3334): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 2840): 
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f207cc1:true
,I/CalendarProvider2( 3315): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3315): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/LocalBluetoothProfileManager( 3334): Adding local A2DP profile
D/BluetoothManagerService(  822): Message: 30
,V/Herrevad( 1770): NQAS connected
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 2389): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1259): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3334): Adding local HEADSET profile
,D/BluetoothManagerService(  822): Message: 30
,I/ActivityManager(  822): Start proc 3412:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 2389): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2389): Accept thread started.
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3334): Adding local MAP profile
D/BluetoothMap( 3334): Create BluetoothMap proxy object
D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3334): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3334): finishStartingService: stopping service
,D/BluetoothA2dp( 3334): Proxy object connected
,D/A2dpProfile( 3334): Bluetooth service connected
,D/BluetoothInputDevice( 3334): Proxy object connected
,D/HidProfile( 3334): Bluetooth service connected
,D/BluetoothPan( 3334): BluetoothPAN Proxy object connected
,D/PanProfile( 3334): Bluetooth service connected
,D/BluetoothMap( 3334): Proxy object connected
,D/MapProfile( 3334): Bluetooth service connected
D/BluetoothMap( 3334): getConnectedDevices()
,D/BluetoothPbap( 3334): Proxy object connected
D/PbapServerProfile( 3334): Bluetooth service connected
,I/ActivityManager(  822): Killing 2747:android.process.acore/u0a5 (adj 15): empty #17
,D/BuaReceiver( 3412): ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset( 3334): Proxy object connected
,D/HeadsetProfile( 3334): Bluetooth service connected
,I/ActivityManager(  822): Start proc 3434:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/Atfwd_Daemon(  375): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  375): ATFWD --> QMI Port : rmnet_usb0
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Atfwd_Daemon(  375): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
,I/Atfwd_Daemon(  375): Trying to register 8 commands:
,I/Atfwd_Daemon(  375): cmd0: +CKPD
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd1: +CTSA
,I/ActivityManager(  822): Start proc 3457:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  822): Killing 1615:com.google.android.keep/u0a79 (adj 15): empty #17
I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd2: +CFUN
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd3: +CMAR
,I/ContactLocale( 3434): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd4: +CDIS
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd5: +CRSL
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd6: +CSS
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  375): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  375): Registered AT Commands event handler
,I/ActivityManager(  822): Start proc 3477:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  822): Killing 2809:com.qualcomm.telephony/1001 (adj 15): empty #17
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 2840): 
,D/PackageBroadcastService( 1770): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Loading module APK com.google.android.play.games
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 2840): 
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 2840): 
,I/ActivityManager(  822): Start proc 3497:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,I/ActivityManager(  822): Killing 2930:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 2840): 
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 2840): 
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 2840): 
,I/jxcore-log( 2840): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 2840): 
,W/ResourcesManager( 3497): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3497): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3497): VM with version 2.1.0 has multidex support
I/MultiDex( 3497): install
I/MultiDex( 3497): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3497): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3497): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  822): Killing 3086:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ConfigFetchService( 1770): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1770): launchTask
,V/ConfigFetchTask( 1770): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UeiSurP6pq8-2XQ2G7F2YC4DEPkE13YwyKu7usgf8JzneNK43rYTSSjpTuFbN8_mjtG5Mjf9i93cxcQDXcFBb5u1OWTlBOodGg6zIY0GsR4aB7nppdDu32hFmm-nVTOWCJqlpcpDbf2iOGuDYSwNrz0F2KUADdnTDKSEEkG1U53kTTDI7NcYcH4GGISrcLX-wZWhdR
,I/GoogleURLConnFactory( 1770): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
,I/PeopleContactsSync( 1770): CP2 sync disabled
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 1770): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1770): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1770): No vision deps
,I/ActivityManager(  822): Start proc 3527:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/iu.UploadsManager( 1770): End new media; added: 0, uploading: 0, time: 63 ms
,I/UpdateIcingCorporaServi( 1526): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1526): UpdateCorporaTask done [took 158 ms] updated apps [took 158 ms] 
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1770): fetch service done; releasing wakelock
,I/ConfigFetchService( 1770): stopping self
,I/art     ( 1770): Explicit concurrent mark sweep GC freed 29804(1864KB) AllocSpace objects, 15(240KB) LOS objects, 35% free, 28MB/44MB, paused 1.257ms total 34.559ms
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 3527): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3527):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3527):   adb logcat -s GAv4
,W/GAv4    ( 3527): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3527): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3527): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3527): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/ResourcesManager( 3527): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  822): Start proc 3563:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  822): Killing 3152:com.google.android.gms:car/u0a11 (adj 15): empty #17
,W/ResourcesManager( 3563): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GAV2    ( 3172): Thread[GAThread,5,main]: No campaign data found.
,V/JNIHelp ( 3527): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3527): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 1770): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,I/art     (  822): Explicit concurrent mark sweep GC freed 11049(514KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.623ms total 46.504ms
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Icing   ( 1770): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  822): Start proc 3593:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  822): Killing 3172:com.google.android.gm/u0a78 (adj 15): empty #17
,I/Icing   ( 1770): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,I/MusicStore( 3593): Database version: 120
,W/ResourcesManager( 3593): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3593): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3593): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/ProviderInstaller( 3593): Installed default security provider GmsCore_OpenSSL,
D/AndroidMusic( 3593): GMSCore installation verified
,I/ConfigStore( 3593): Config Database version: 1
,I/MediaRouter( 3593): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 3593): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3593): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 3593): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3593): Using platform SSLCertificateSocketFactory
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 8547(442KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 1.023ms total 36.302ms
,D/GCM     ( 1259): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/MusicLeanback( 3593): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/SQLiteLog( 3315): (284) automatic index on view_events(_id)
,I/ActivityManager(  822): Start proc 3635:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 216us total 12.456ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 10.319ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 383us total 9.371ms
,I/MediaStoreImporter( 3593): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  822): Killing 3206:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3662:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  822): Killing 3244:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,D/SprintDMReceiver( 3662): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3662): simOperator:  IMSI: null
D/SprintDMReceiver( 3662): Not Sprint UICC, don't do anything.
,I/ActivityManager(  822): Killing 3289:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  822): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/BackupManagerService(  822): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,V/BackupManagerService(  822): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  822): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@376fe72e
,I/SystemUpdateService( 1770): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599961 ms
,D/SystemUpdateService( 1770): onDestroy
,V/BackupManagerService(  822): Scheduling immediate backup pass
,V/BackupManagerService(  822): Running a backup pass
,V/BackupManagerService(  822): clearing pending backups
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/PerformBackupTask(  822): Beginning backup of 14 targets
,D/PerformBackupTask(  822): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  822): doBackup() invoked
V/GmsNetworkLocationProvi( 1808): DISABLE
V/GmsNetworkLocationProvi( 1808): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/PMBA    (  822): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/Launcher( 1398): Deferring update until onResume
,I/BackupRestoreController(  822): Getting widget state for user: 0
,W/GmsBackupTransport( 1808): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1808): starting performBackup for @pm@
,V/GmsBackupTransport( 1808): performBackup done for @pm@
,I/ActivityManager(  822): Start proc 3685:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsNetworkLocationProvi( 1808): ENABLE
V/GmsNetworkLocationProvi( 1808): SET-REQUEST
,V/GmsNetworkLocationProvi( 1808): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.97 rxSuccessRate=11.83 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 6 -> obsolete
,I/art     (  822): Explicit concurrent mark sweep GC freed 20231(1112KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.110ms total 65.647ms
,I/Babel   ( 3035): connection state changed from UNKNOWN to CONNECTED
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1259): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1259): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1259): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1259): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1808): Error sending final backup to server: 
W/GmsBackupTransport( 1808): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1808): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1808): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1808): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1808): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1808): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1808): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1808): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1808): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1808): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1808): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1808): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1808): 	... 1 more
,D/BackupManagerService(  822): Now staging backup of com.google.android.talk
,I/GAv4    ( 3685): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3685):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3685):   adb logcat -s GAv4
,D/BackupManagerService(  822): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  822): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  822): Now staging backup of com.android.sharedstoragebackup
,W/GAv4    ( 3685): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/BackupManagerService(  822): Now staging backup of com.google.android.gm
,D/BackupManagerService(  822): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  822): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  822): Now staging backup of com.android.nfc
,W/GAv4    ( 3685): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/BackupManagerService(  822): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  822): Now staging backup of com.android.vending
,W/GAv4    ( 3685): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/BackupManagerService(  822): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  822): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  822): Now staging backup of android
,D/BackupManagerService(  822): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1808): Next backup will happen in 43199951 millis.
,I/BackupManagerService(  822): Backup pass finished.
,I/WebViewFactory( 3685): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3685): Time to load native libraries: 1 ms (timestamps 3914-3915)
,I/LibraryLoader( 3685): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3685): Binding Chromium to main looper Looper (main, tid 1) {17d6097a}
,I/LibraryLoader( 3685): Expected native library version number "",actual native library version number ""
,I/chromium( 3685): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3685): Initializing chromium process, singleProcess=true
,W/art     ( 3685): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3685): ApplicationContext is null in ApplicationStatus
,W/chromium( 3685): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3685): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3685): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3685): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3685): Requires BLUETOOTH permission
,I/NSApplication( 3685): Starting up...
,I/ActivityManager(  822): Start proc 3745:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  822): Killing 3067:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=-5ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 21:14:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454534054251], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454534054228]}
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1068): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  822): Start proc 3766:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  822): Killing 3334:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3375:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
V/MusicLeanback( 3593): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3662): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3662): simOperator:  IMSI: null
D/SprintDMReceiver( 3662): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599964 ms
,D/SystemUpdateService( 1770): onDestroy
,D/GCM     ( 1259): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1259): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1770): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3497): callingUid 10011, callindPid: 3497
,D/LocationInitializer( 1770): Restart initialization of location
,I/ActivityManager(  822): Start proc 3791:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,E/MDM     ( 1808): [158] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Gmail   ( 3791): getAccountsCursor
,D/ActivityThread( 3791): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  822): Start proc 3815:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 3791): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.97 rxSuccessRate=11.83 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 6 -> obsolete
,W/ActivityManager(  822): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3815): EasService.onCreate
,I/Exchange( 3815): RestartPingTask
,I/Gmail   ( 3791): Observing account changes for notifications
,I/Gmail   ( 3791): getAccountsCursor
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 3815): RestartPingsTask did not start any pings.
I/Exchange( 3815): PSS stopIfIdle
I/Exchange( 3815): PSS has no active accounts; stopping service.
,I/Exchange( 3815): onDestroy
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3791): (283) recovered 63 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/MusicLeanback( 3593): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3662): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3662): simOperator:  IMSI: null
D/SprintDMReceiver( 3662): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,W/ResourcesManager( 3035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SystemUpdateService( 1770): showing system update notification
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Gmail   ( 3791): notifyAccountChanged
,I/Gmail   ( 3791): getAccountsCursor
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3791): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3791): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ValidateNoPeople(  822): skipping global notification
,V/JNIHelp ( 3035): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Gmail   ( 3791): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3791): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599933 ms
,D/SystemUpdateService( 1770): onDestroy
,I/ProviderInstaller( 3035): Installed default security provider GmsCore_OpenSSL
I/Gmail   ( 3791): getAccountsCursor
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1259): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/NotifUtils( 3791): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,D/AuthorizationBluetoothService( 1259): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1770): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1808): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1770): Restart initialization of location
,I/NotifUtils( 3791): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,D/PackageBroadcastService( 1770): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1770): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1526): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1398): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f9ec8e0 new=com.google.android.velvet.VelvetApplication@2f9ec8e0
,I/Icing   ( 1770): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{3728cbe6 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/art     (  822): Explicit concurrent mark sweep GC freed 20830(995KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.447ms total 52.380ms
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{1ff23a41 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,V/Herrevad( 1770): NQAS connected
,I/UpdateIcingCorporaServi( 1526): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,D/GCM     ( 1259): Connected
,D/GCM     ( 1259): Message class com.google.f.a.a.p
,I/jxcore-log( 2840): Test app app.js loaded
I/jxcore-log( 2840): 
,I/chromium( 2840): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2840): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ccfd99 added. We now have 1 listener(s)
,I/jxcore-log( 2840): BLE advertisement is supported
I/jxcore-log( 2840): 
,I/ConfigService( 1259): onDestroy
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{10f248d0 u0 com.qualcomm.atfwd/.AtFwdService}
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0,
,I/MusicLeanback( 3593): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3593): Stop autocaching.
,E/GmsUtils( 3593): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3593): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3791): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  822): Killing 3457:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3477:com.android.musicfx/u0a18 (adj 15): empty #17
,I/CheckinService( 1770): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{278d50b4 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3108): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3108): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3108): [1] 5.onFinished: Scheduling replication attempt 1.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.56 rxSuccessRate=3.09 targetRoamBSSID=any RSSI=-52
,I/ActivityManager(  822): Killing 3815:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3527:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,D/Finsky  ( 3108): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3108): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 28607(1487KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.510ms total 54.970ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3108): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3108): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3108): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 3108): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3108): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1),
,D/DeviceConnectionService( 1808): client connected with version: 7571000
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.67 rxSuccessRate=1.70 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 30359(1432KB) AllocSpace objects, 10(254KB) LOS objects, 32% free, 33MB/49MB, paused 1.391ms total 86.698ms
,D/Finsky  ( 3108): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3108): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3108): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  822): Start proc 3923:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAV2    ( 3923): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksApp( 3923): Created application version: 3.6.8 (30608)
,E/HttpOperation( 3563): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3563): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3563): 	at jdm.a(PG:82)
E/HttpOperation( 3563): 	at jcs.o(PG:406)
E/HttpOperation( 3563): 	at jcn.a(PG:1379)
E/HttpOperation( 3563): 	at jcs.i(PG:143)
E/HttpOperation( 3563): 	at blb.a(PG:3937)
E/HttpOperation( 3563): 	at czp.a(PG:18188)
E/HttpOperation( 3563): 	at czp.a(PG:9081)
E/HttpOperation( 3563): 	at czq.run(PG:1686)
E/HttpOperation( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3563): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3563): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3563): 	at jdj.a(PG:4091)
E/HttpOperation( 3563): 	at jdj.a(PG:1125)
E/HttpOperation( 3563): 	at jdm.a(PG:77)
E/HttpOperation( 3563): 	... 12 more
E/HttpOperation( 3563): Caused by: faj: BadAuthentication
E/HttpOperation( 3563): 	at fal.a(PG:38)
E/HttpOperation( 3563): 	at jdj.a(PG:4089)
E/HttpOperation( 3563): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3563): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3563): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3563): 	at jdm.a(PG:82)
E/HttpOperation( 3563): 	at jcs.o(PG:406)
E/HttpOperation( 3563): 	at jcn.a(PG:1379)
E/HttpOperation( 3563): 	at jcs.i(PG:143)
E/HttpOperation( 3563): 	at hec.a(PG:42)
E/HttpOperation( 3563): 	at hee.a(PG:102)
E/HttpOperation( 3563): 	at czr.a(PG:65)
E/HttpOperation( 3563): 	at kka.a(PG:108)
E/HttpOperation( 3563): 	at czp.a(PG:19176)
E/HttpOperation( 3563): 	at czp.a(PG:9081)
E/HttpOperation( 3563): 	at czq.run(PG:1686)
E/HttpOperation( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3563): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3563): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3563): 	at jdj.a(PG:4091)
E/HttpOperation( 3563): 	at jdj.a(PG:1125)
E/HttpOperation( 3563): 	at jdm.a(PG:77)
E/HttpOperation( 3563): 	... 15 more
E/HttpOperation( 3563): Caused by: faj: BadAuthentication
E/HttpOperation( 3563): 	at fal.a(PG:38)
E/HttpOperation( 3563): 	at jdj.a(PG:4089)
E/HttpOperation( 3563): 	... 17 more
E/ExperimentLoader( 3563): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3563): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3563): 	at jdm.a(PG:82)
E/ExperimentLoader( 3563): 	at jcs.o(PG:406)
E/ExperimentLoader( 3563): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3563): 	at jcs.i(PG:143)
E/ExperimentLoader( 3563): 	at hec.a(PG:42)
E/ExperimentLoader( 3563): 	at hee.a(PG:102)
E/ExperimentLoader( 3563): 	at czr.a(PG:65)
E/ExperimentLoader( 3563): 	at kka.a(PG:108)
E/ExperimentLoader( 3563): 	at czp.a(PG:19176)
E/ExperimentLoader( 3563): 	at czp.a(PG:9081)
E/ExperimentLoader( 3563): 	at czq.run(PG:1686)
E/ExperimentLoader( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3563): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3563): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3563): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3563): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3563): 	at jdm.a(PG:77)
E/ExperimentLoader( 3563): 	... 15 more
E/ExperimentLoader( 3563): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3563): 	at fal.a(PG:38)
E/ExperimentLoader( 3563): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3563): 	... 17 more
,I/BooksSync( 3923): Starting books sync for 61035162, extras: ade
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 80519, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 3923): GmsCore Version = 7.8.99 (2134222-430)
,I/ActivityManager(  822): Start proc 3956:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3923): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3923): Soft error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3923): Sync error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3923): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 81851, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3662:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17,
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 23690(1356KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 1.058ms total 23.381ms
,V/KeepSync( 3956): Connecting to GoogleApiClient
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3956): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3956): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3956): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3956): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3956): IOException
E/KeepSync( 3956): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3956): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3956): 	,at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3956): ,	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
,E/KeepSync( 3956): ,	at com.google.api.client.http.HttpRequest.execute(SourceFile:858),
E/KeepSync( 3956): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3956): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3956): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3956): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3956): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3956): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3956): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3956): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3956): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3956): 	... 10 more
W/KeepSync( 3956): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 82113, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3685:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3986:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3986): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3986):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3986):   adb logcat -s GAv4
,W/GAv4    ( 3986): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3986): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3986): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3745:com.android.chrome/u0a40 (adj 15): empty #17,
,I/Keyboard.Facilitator.LanguageModelFlusher( 1237): run()
I/Keyboard.Facilitator( 1237): flushDynamicLanguageModels()
,I/ConfigService( 1259): onCreate
,I/GAV2    ( 3923): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1259): onDestroy
,D/Finsky  ( 3108): [300] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3108): [300] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=2.21 targetRoamBSSID=any RSSI=-52
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 34624(1594KB) AllocSpace objects, 7(112KB) LOS objects, 31% free, 34MB/50MB, paused 1.368ms total 59.078ms
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3108): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3108): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3108): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.60 rxSuccessRate=2.09 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3108): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3108): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3108): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.69 rxSuccessRate=1.96 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (365 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  822): Display changed displayId=0
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000,
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  822): Entering dreamland.,
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  822): Dozing...
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1237): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
,I/kickstart(  872): STATUS: 950272 bytes transferred in 0.991231 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3108): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3108): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3108): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksSync( 3923): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3923): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3563): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3563): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3563): 	at jdm.a(PG:82)
E/HttpOperation( 3563): 	at jcs.o(PG:406)
E/HttpOperation( 3563): 	at jcn.a(PG:1379)
E/HttpOperation( 3563): 	at jcs.i(PG:143)
E/HttpOperation( 3563): 	at blb.a(PG:3937)
E/HttpOperation( 3563): 	at czp.a(PG:18188)
E/HttpOperation( 3563): 	at czp.a(PG:9081)
E/HttpOperation( 3563): 	at czq.run(PG:1686)
E/HttpOperation( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3563): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3563): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3563): 	at jdj.a(PG:4091)
E/HttpOperation( 3563): 	at jdj.a(PG:1125)
E/HttpOperation( 3563): 	at jdm.a(PG:77)
E/HttpOperation( 3563): 	... 12 more
E/HttpOperation( 3563): Caused by: faj: BadAuthentication
E/HttpOperation( 3563): 	at fal.a(PG:38)
E/HttpOperation( 3563): 	at jdj.a(PG:4089)
E/HttpOperation( 3563): 	... 14 more
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3923): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3923): Soft error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3923): Sync error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3923): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140014, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 3563): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3563): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3563): 	at jdm.a(PG:82)
E/HttpOperation( 3563): 	at jcs.o(PG:406)
E/HttpOperation( 3563): 	at jcn.a(PG:1379)
E/HttpOperation( 3563): 	at jcs.i(PG:143)
E/HttpOperation( 3563): 	at hec.a(PG:42)
E/HttpOperation( 3563): 	at hee.a(PG:102)
E/HttpOperation( 3563): 	at czr.a(PG:65)
E/HttpOperation( 3563): 	at kka.a(PG:108)
E/HttpOperation( 3563): 	at czp.a(PG:19176)
E/HttpOperation( 3563): 	at czp.a(PG:9081)
E/HttpOperation( 3563): 	at czq.run(PG:1686)
E/HttpOperation( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3563): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3563): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3563): 	at jdj.a(PG:4091)
E/HttpOperation( 3563): 	at jdj.a(PG:1125)
E/HttpOperation( 3563): 	at jdm.a(PG:77)
E/HttpOperation( 3563): 	... 15 more
E/HttpOperation( 3563): Caused by: faj: BadAuthentication
E/HttpOperation( 3563): 	at fal.a(PG:38)
E/HttpOperation( 3563): 	at jdj.a(PG:4089)
E/HttpOperation( 3563): 	... 17 more
E/ExperimentLoader( 3563): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3563): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3563): 	at jdm.a(PG:82)
E/ExperimentLoader( 3563): 	at jcs.o(PG:406)
E/ExperimentLoader( 3563): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3563): 	at jcs.i(PG:143)
E/ExperimentLoader( 3563): 	at hec.a(PG:42)
E/ExperimentLoader( 3563): 	at hee.a(PG:102)
E/ExperimentLoader( 3563): 	at czr.a(PG:65)
E/ExperimentLoader( 3563): 	at kka.a(PG:108)
E/ExperimentLoader( 3563): 	at czp.a(PG:19176)
E/ExperimentLoader( 3563): 	at czp.a(PG:9081)
E/ExperimentLoader( 3563): 	at czq.run(PG:1686)
E/ExperimentLoader( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3563): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3563): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3563): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3563): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3563): 	at jdm.a(PG:77)
E/ExperimentLoader( 3563): 	... 15 more
E/ExperimentLoader( 3563): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3563): 	at fal.a(PG:38)
E/ExperimentLoader( 3563): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3563): 	... 17 more
,V/KeepSync( 3956): Connecting to GoogleApiClient
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 140117, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3956): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3956): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3956): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3956): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3956): IOException
E/KeepSync( 3956): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3956): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3956): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3956): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3956): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3956): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3956): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3956): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3956): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3956): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3956): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3956): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3956): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3956): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3956): 	... 10 more
,W/KeepSync( 3956): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 140953, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1259): Explicit concurrent mark sweep GC freed 37819(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.722ms total 40.562ms
,I/VacuumService( 1259): Vacuum at: now=1454534178932 tag=VacuumService
,V/GoogleAuthProtoRequest( 3635): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3108): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3108): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3108): [1] 5.onFinished: Giving up after 6 failures.
,I/art     (  822): Explicit concurrent mark sweep GC freed 46921(2MB) AllocSpace objects, 14(412KB) LOS objects, 31% free, 34MB/50MB, paused 1.720ms total 87.506ms
,W/ExperimentUpdateService( 3635): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3635): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3635): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3635): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3635): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3635): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3635): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3635): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3635): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3635): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3635): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3635): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1259): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259): No account for auth token provided
,W/Uploader( 1259):  no longer exists, so no auth token.
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1259): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1259): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1259): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1259): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1259): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1259): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3635): [398] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3635): [398] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3635): [398] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3635): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3635): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3635): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3635): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3635): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3635): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3635): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3635): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3635): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3635): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1237): run()
I/Keyboard.Facilitator( 1237): flushDynamicLanguageModels()
,I/ConfigService( 1259): onCreate
,I/BooksSync( 3923): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3923): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3923): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3923): Soft error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3923): Sync error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3923): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230721, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1259): onDestroy
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,I/jxcore-log( 2840): --= Surplus to requirements =--
I/jxcore-log( 2840): 
I/jxcore-log( 2840): ****TEST TOOK:  ms ****
I/jxcore-log( 2840): 
I/jxcore-log( 2840): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2840): 
,D/AndroidRuntime( 4066): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4066): CheckJNI is OFF
,D/AndroidRuntime( 4066): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  822): Killing 2840:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{177a17ad com.example.hello/10273} due to missing metadata
,I/WindowState(  822): WIN DEATH: Window{d6a1554 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 2840
W/ActivityManager(  822): Force removing ActivityRecord{3d7b21fc u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0
,W/ActivityManager(  822): Spurious death for ProcessRecord{13407f7c 2840:com.test.thalitest/u0a265}, curProc for 2840: null
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1237): resetDictionaries() : en_US
,D/BuaReceiver( 3412): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator.DecoderInitializer( 1237): run()
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1237): createOrResetDecoder
,I/art     ( 1068): Explicit concurrent mark sweep GC freed 54736(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 959us total 68.392ms
,D/VoicemailCleanupService( 3434): Cleaning up data for package: com.test.thalitest
,I/art     (  822): Explicit concurrent mark sweep GC freed 24589(1408KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.380ms total 100.974ms
I/art     (  822): WaitForGcToComplete blocked for 98.094ms for cause Explicit
,I/ActivityManager(  822): Start proc 4082:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ConfigService( 1259): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1237): run()
,I/art     ( 1526): Explicit concurrent mark sweep GC freed 769(42KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 9.047ms total 146.250ms
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 2840 uid 10265
,I/Keyboard.Facilitator( 1237): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1237): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1237): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1237): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1237): run()
I/StatsUtilsManager( 1237): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1237): shouldRecordStats() = Too Soon
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager(  822): Start proc 4104:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 13.253ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 224us total 9.063ms
,I/art     ( 1398): Explicit concurrent mark sweep GC freed 10138(530KB) AllocSpace objects, 11(1212KB) LOS objects, 31% free, 35MB/51MB, paused 929us total 27.817ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 11.075ms
,W/LocationOracleImpl( 1526): Best location was null
,W/ContextImpl( 4104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/HotwordRecognitionRnr( 1526): Starting hotword detection.
I/MicrophoneInputStream( 1526): mic_starting com.google.android.apps.gsa.speech.audio.u@217e7d91
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4d8d000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1526): mic_started com.google.android.apps.gsa.speech.audio.u@217e7d91
E/NetworkScheduler.SchedulerReceiver( 1259): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1259): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1770): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1770): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1770): Removing dialog suppression flag for package com.test.thalitest
,W/Launcher( 1398): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f9ec8e0 new=com.google.android.velvet.VelvetApplication@2f9ec8e0
,I/UpdateIcingCorporaServi( 1526): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  822): Explicit concurrent mark sweep GC freed 8203(391KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.546ms total 210.441ms
,D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1770): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1770): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1770): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  822): Start proc 4146:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/HotwordWorker( 1526): onReady
,I/ConfigFetchService( 1770): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1770): service connected
,I/Icing   ( 1770): doRemovePackageData com.test.thalitest
,I/PeopleContactsSync( 1770): CP2 sync disabled
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2355c394}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,W/BaseAppContext( 1770): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1526): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
,D/Launcher.Workspace( 1398): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1398): 11683562 - stripEmptyScreens()
,I/art     ( 4066): System.exit called, status: 0
I/AndroidRuntime( 4066): VM exiting with result code 0.
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1722115347
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/GAv4    ( 4146): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4146):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4146):   adb logcat -s GAv4
,W/GAv4    ( 4146): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4146): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4146): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4146): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4146): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4146): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4146): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4146): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4146): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4146): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4146): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4146): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4146): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4146): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4146): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4146): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4146): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4146): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/GAv4    ( 4146): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4146): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4146): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4146): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4146): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4146): 	at aen.run(PG:536)
,W/GAv4    ( 4146): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4146): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4146): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4146): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4146): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4146): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4146): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4146): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4146): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4146): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4146): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4146): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4146): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4146): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4146): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4146): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4146): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4146): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4146): 	at aej.c(PG:139)
E/SQLiteDatabase( 4146): 	at aej.b(PG:398)
E/SQLiteDatabase( 4146): 	at agf.f(PG:417)
E/SQLiteDatabase( 4146): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4146): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4146): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4146): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4146): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 4146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4146): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4146): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4146): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4146): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4146): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4146): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4146): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4146): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4146): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4146): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4146): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4146): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  822): Start proc 4184:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{23240fcf token=Token{12cbe82e ActivityRecord{224a7aa9 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4146): Sending signal. PID: 4146 SIG: 9
I/HotwordDetector( 1526): Closing mic
I/MicrophoneInputStream( 1526): mic_close com.google.android.apps.gsa.speech.audio.u@217e7d91
,E/lowmemorykiller(  256): Error writing /proc/4146/oom_score_adj; errno=22
,E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  822): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  822): android.os.TransactionTooLargeException
W/ActivityManager(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  822): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  822): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  822): 	at android.os.Binder.execTransact(Binder.java:446)
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1526): Hotword detection finished
,I/HotwordRecognitionRnr( 1526): Stopping hotword detection.
,I/ActivityManager(  822): Start proc 4202:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/OpenGLRenderer( 1398): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ActivityManager(  822): Spurious death for ProcessRecord{23bd6e71 4202:com.google.android.apps.docs/u0a46}, curProc for 4146: null
,I/ActivityManager(  822): Killing 3766:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/Search.SharedPreferencesProto( 1526): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4184): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4184): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4184): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4184): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4184): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4184): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4184): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4184): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4184): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4184): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4184): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4184): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4184): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4184): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 4184): FATAL EXCEPTION: main
E/AndroidRuntime( 4184): Process: com.android.documentsui, PID: 4184
E/AndroidRuntime( 4184): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4184): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4184): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4184): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4184): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4184): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4184): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4184): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4184): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4184): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4184): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4184): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4184): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4184): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4184): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4184): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4184): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4184): 	... 9 more
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  822): Validating map...,
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,D/OpenGLRenderer(  822): Enabling debug mode 0
,I/ActivityManager(  822): Start proc 4228:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  822): Killing 3035:com.google.android.talk/u0a61 (adj 15): empty #17
,E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1770): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,I/ActivityManager(  822): Killing 3791:com.google.android.gm/u0a78 (adj 15): empty #17
,D/ExternalStorage( 4228): After updating volumes, found 1 active roots
,E/Icing   ( 1770): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1770): Could not init tag ds.tag.deleted
,I/GAv4    ( 4202): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4202):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4202):   adb logcat -s GAv4
,I/Icing   ( 1770): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1770): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1770): Writing status failed
E/Icing   ( 1770): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/ActivityManager(  822): Killing 2302:com.google.android.calendar/u0a37 (adj 15): empty #17
,W/GAv4    ( 4202): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4202): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4202): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4202): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4202): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4202): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4202): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4202): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4202): Opening the database failed, dropping the table and recreating it,
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4202): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4202): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4202): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4202): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4202): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4202): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4202): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4    ( 4202): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4202): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2355c394}
,E/SQLiteDatabase( 4202): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4202): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4202): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4202): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4202): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4202): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4202): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4202): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4202): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4202): 	at aej.c(PG:139)
E/SQLiteDatabase( 4202): 	at aej.b(PG:398)
E/SQLiteDatabase( 4202): 	at agf.f(PG:417)
E/SQLiteDatabase( 4202): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4202): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4202): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4202): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4202): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4202): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4202): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4202): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4202): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4202): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4202): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4202): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4202): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ErrorNotificationActivity( 4202): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,V/JNIHelp ( 4202): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/OpenGLRenderer( 4202): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,I/ProviderInstaller( 4202): Installed default security provider GmsCore_OpenSSL
,D/Atlas   ( 4202): Validating map...
,V/WindowManager(  822): Adding window Window{98217a7 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{1bb16337 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  822): Adding window Window{2203ffd u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{98217a7 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SQLiteDatabase( 4202): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4202): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4202): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4202): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4202): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4202): 	at aej.c(PG:139)
E/SQLiteDatabase( 4202): 	at aej.a(PG:358)
E/SQLiteDatabase( 4202): 	at aej.a(PG:345)
E/SQLiteDatabase( 4202): 	at agf.c(PG:884)
E/SQLiteDatabase( 4202): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4202): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4202): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4202): 	at java.lang.Thread.run(Thread.java:818)
E/GAv4    ( 4202): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SQLiteDatabase( 4202): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4202): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4202): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4202): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4202): 	at aej.c(PG:139)
E/SQLiteDatabase( 4202): 	at aej.a(PG:358)
E/SQLiteDatabase( 4202): 	at aej.a(PG:345)
E/SQLiteDatabase( 4202): 	at agf.d(PG:281)
E/SQLiteDatabase( 4202): 	at agf.b(PG:312)
E/SQLiteDatabase( 4202): 	at agf.a(PG:221)
E/SQLiteDatabase( 4202): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4202): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4202): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4202): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4202): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4202): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AbstractDatabaseInstance( 4202): Failed to query Account133 object
E/AbstractDatabaseInstance( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4202): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4202): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4202): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4202): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4202): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4202): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4202): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4202): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4202): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4202): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4202): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4202): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4202): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4202): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4202): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AbstractDatabaseInstance( 4202): Failed to query Account133 object
E/AbstractDatabaseInstance( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4202): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4202): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4202): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4202): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4202): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4202): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4202): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4202): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4202): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4202): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4202): 	at java.lang.Thread.run(Thread.java:818)
E/DatabaseUtils( 4202): Writing exception to parcel
E/DatabaseUtils( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteDatabase.open,(SQLiteDatabase.java:791)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4202): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4202): 	at ael.a(PG:1521)
E/DatabaseUtils( 4202): 	at hix$a.a(PG:125)
E/DatabaseUtils( 4202): 	at aej.c(PG:139)
E/DatabaseUtils( 4202): 	at aej.a(PG:358)
E/DatabaseUtils( 4202): 	at aej.a(PG:345)
E/DatabaseUtils( 4202): 	at agf.d(PG:281)
E/DatabaseUtils( 4202): 	at agf.b(PG:312)
E/DatabaseUtils( 4202): 	at agf.a(PG:221)
E/DatabaseUtils( 4202): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4202): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4202): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4202): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4202): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4202): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4202): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4202): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4202): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4202): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKE,MIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4202): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4202): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4202): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4202): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4202): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4202): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4202): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4202): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/Documents( 4184): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4184): Update found 6 roots in 1072ms
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4202): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4202): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4202): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4202): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4202): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 4202): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/CAKEMIX_CRASHED( 4202): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 4202): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 4202): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 4202): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 4202): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 4202): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED( 4202): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4202): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4202): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4202): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4202): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4202): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4202): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4202): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 4202): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 4202): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 4202): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 4202): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 4202): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/CAKEMIX_CRASHED( 4202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 4202): 	... 4 more
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
I/Process ( 4202): Sending signal. PID: 4202 SIG: 9
,I/WindowState(  822): WIN DEATH: Window{98217a7 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,I/WindowState(  822): WIN DEATH: Window{2203ffd u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,I/ActivityManager(  822): Process com.google.android.apps.docs (pid 4202) has died,
,W/ActivityManager(  822): Force removing ActivityRecord{224a7aa9 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,E/SQLiteDatabase( 1259): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1259): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1259): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1259): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1259): Opened phenotype.db in read-only mode
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818),
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 1259): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1259): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1259): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1259): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1259): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1259): Opened phenotype.db in read-only mode
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database,
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8),
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): ,	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): ,	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database,
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): ,	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): ,	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): ,	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102),
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178),
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818),
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416),
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): ,	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178),
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): ,	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	,at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	,at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): ,	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): ,	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818),
I/art     ( 1259): Explicit concurrent mark sweep GC freed 50698(3MB) AllocSpace objects, 12(953KB) LOS objects, 36% free, 27MB/43MB, paused 1.196ms total 50.544ms
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102),
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
,E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DatabaseUtils( 1259): Writing exception to parcel
E/DatabaseUtils( 1259): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 1259): 	,at com.google.android.gsf.subscribedfeeds.AbstractSyncableContentProvider.delete(AbstractSyncableContentProvider.java:312)
E/DatabaseUtils( 1259): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/DatabaseUtils( 1259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
E/DatabaseUtils( 1259): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
V/KeepSync( 3956): Connecting to GoogleApiClient
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8),
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153),
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	,at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,W/FileUtils( 1770): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
W/AtomicFile(  822): Couldn't rename file /data/system/sync/status.bin to backup file /data/system/sync/status.bin.bak
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 1770): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1770): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 1770): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 1770): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:982)
W/ServiceConnection( 1770): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:182)
W/ServiceConnection( 1770): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 1770): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 1770): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 1770): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 1770): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1770): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 1770): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 1770): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 1770): 	... 7 more
W/SyncManager(  822): Error writing status
W/SyncManager(  822): java.io.IOException: Couldn't create directory /data/system/sync/status.bin
W/SyncManager(  822): 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
W/SyncManager(  822): 	at com.android.server.content.SyncStorageEngine.writeStatusLocked(SyncStorageEngine.java:2406)
W/SyncManager(  822): 	at com.android.server.content.SyncStorageEngine.stopSyncEvent(SyncStorageEngine.java:1401)
W/SyncManager(  822): 	at com.android.server.content.SyncManager$SyncHandler.stopSyncEvent(SyncManager.java:3160)
W/SyncManager(  822): 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledLocked(SyncManager.java:2843)
W/SyncManager(  822): 	at com.android.serv,er.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2070)
W/SyncManager(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/SyncManager(  822): 	at android.os.Looper.loop(Looper.java:135)
W/SyncManager(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
I/GLSUser ( 1259): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1259): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1259): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1259): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1259): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1770): (3850) statement aborts at 87: [DELETE FROM AppAuthMetadata112 WHERE ((accountId=?) AND (packageName=?)) AND (certificateHash=?)] disk I/O error
E/EsApplication( 3563): Uncaught exception in background thread Thread[SyncAdapterThread-3,5,main]
E/EsApplication( 3563): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/EsApplication( 3563): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/EsApplication( 3563): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/EsApplication( 3563): 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:544)
E/EsApplication( 3563): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/EsApplication( 3563): 	at czp.a(PG:6863)
E/EsApplication( 3563): 	at czq.run(PG:1612)
E/EsApplication( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/EsApplication( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/EsApplication( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/EsApplication( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/EsApplication( 3563): 	at java.lang.Thread.run(Thread.java:818)
,E/DocListDatabase( 1770): Failed to delete from AppAuthMetadata112
E/DocListDatabase( 1770): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1770): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1770): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.database.f.d(SourceFile:1365)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.database.f.b(SourceFile:1399)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:248)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/DocListDatabase( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/DocListDatabase( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DocListDatabase( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/DriveAsyncService( 1770): disk I/O error (code 3850)
E/DriveAsyncService( 1770): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1770): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DriveAsyncService( 1770): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DriveAsyncService( 1770): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DriveAsyncService( 1770): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DriveAsyncService( 1770): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.database.f.d(SourceFile:1365)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.database.f.b(SourceFile:1399)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:248)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/DriveAsyncService( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/DriveAsyncService( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Handling failure
,V/KeepSync( 3956): GoogleApiClient failed to connect with error code: 8
E/SQLiteLog( 3956): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/FileUtils( 1770): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
W/ServiceConnection( 1770): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1770): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 1770): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 1770): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:982)
W/ServiceConnection( 1770): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:182)
W/ServiceConnection( 1770): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 1770): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 1770): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 1770): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 1770): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1770): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 1770): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 1770): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 1770): 	... 7 more
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1259): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/AndroidRuntime( 3956): FATAL EXCEPTION: SyncAdapterThread-3
E/AndroidRuntime( 3956): Process: com.google.android.keep, PID: 3956
E/AndroidRuntime( 3956): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3956): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3956): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 3956): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3956): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3956): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 3956): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 3956): 	at com.android.common.content.SQLiteContentProvider.update(SourceFile:153)
E/AndroidRuntime( 3956): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 3956): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:499)
E/AndroidRuntime( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.u(SourceFile:471)
E/AndroidRuntime( 3956): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:188)
E/AndroidRuntime( 3956): 	,at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ClearcutLoggerIntentService( 1259): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1259): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1259): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClearcutLoggerIntentService( 1259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1259): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,W/AtomicFile(  822): Couldn't rename file /data/system/sync/status.bin to backup file /data/system/sync/status.bin.bak
W/SyncManager(  822): Error writing status
W/SyncManager(  822): java.io.IOException: Couldn't create directory /data/system/sync/status.bin
W/SyncManager(  822): 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
W/SyncManager(  822): 	at com.android.server.content.SyncStorageEngine.writeStatusLocked(SyncStorageEngine.java:2406)
W/SyncManager(  822): 	at com.android.server.content.SyncStorageEngine.stopSyncEvent(SyncStorageEngine.java:1401)
W/SyncManager(  822): 	at com.android.server.content.SyncManager$SyncHandler.stopSyncEvent(SyncManager.java:3160)
W/SyncManager(  822): 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledLocked(SyncManager.java:2843)
W/SyncManager(  822): 	at com.android.server.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2070)
W/SyncManager(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/SyncManager(  822): 	at android.os.Looper.loop(Looper.java:135)
W/SyncManager(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 3563): FATAL EXCEPTION: SyncAdapterThread-3
E/AndroidRuntime( 3563): Process: com.google.android.apps.plus, PID: 3563
E/AndroidRuntime( 3563): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3563): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 3563): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 3563): 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:544)
E/AndroidRuntime( 3563): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 3563): 	at czp.a(PG:6863)
E/AndroidRuntime( 3563): 	at czq.run(PG:1612)
E/AndroidRuntime( 3563): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AndroidRuntime( 3563): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 3563): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3563): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3563): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,W/ResourcesManager(  822): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Search.SharedPreferencesProto( 1526): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1259): onDestroy
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1722115347
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1,
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1,
E/LocSvc_ApiV02(  822): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_ApiV02(  822): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
,E/kickstart(  872): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1,
E/kickstart(  872): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  872): ERROR: function: main:268 Uploading  Image using Sahara protocol failed,
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock,
,E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt FUSION
E/ThermalEngine(  366): modem_clnt_error_cb: with -2 called for clnt 0x6
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb0,
I/Atfwd_Daemon(  375): Modem Out Of Service --> Release ATCOP service client handles, if any
,I/Atfwd_Daemon(  375): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb7
D/        (  358): csd_client_error_cb: error -2 cb_data 0xb602c060
D/        (  358): csd_client_error_cb: MDM reset
,E/        (  358): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2,
,E/        (  358): csd_service_deinit: Error -1 deiniting CSD,
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb1,
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb5,
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb4,
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb2
,I/ThermalEngine(  366): qmi: Instance id 157 for fusion TS
,E/        (  358): csd_service_deinit: notifier handle release rc:0,
,D/        (  358): csd_service_init: qmi_client_notifier_init() successful
,W/WindowManager(  822): App freeze timeout expired.
,V/ImsSenderRxr( 1367): Read packet: 15 bytes
V/ImsSenderRxr( 1367): processResponse
D/ImsSenderRxr( 1367): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsSenderRxr( 1367):  Tag -1 3 213 0
,I/str_params(  358): key: 'all_call_states' value: ''
,E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt MODEM
I/str_params(  358): key: 'all_call_states' value: ''
I/str_params(  358): key: 'all_call_states' value: ''
,E/LocSvc_ApiV02(  822): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
E/LocSvc_ApiV02(  822): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error

```
