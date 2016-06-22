#### Test 721454317367600_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
06-22 07:43:43.263  1017  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:43:43.263  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
--------- beginning of main
06-22 07:43:43.273  5200  5200 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
06-22 07:43:43.273  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.273  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.273  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:43.273  1017  1389 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.273  1017  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:43.273  1017  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
06-22 07:43:43.273  1017  1389 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
06-22 07:43:43.273  1017  1389 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
06-22 07:43:43.283  5585  5612 D Compatibility: onHandleIntent()
06-22 07:43:43.283  1017  3035 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
06-22 07:43:43.283  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.283  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.283  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.283  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.293  5585  5612 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10170, android.intent.extra.user_handle=0}]
06-22 07:43:43.293  5613  5613 E Zygote  : MountEmulatedStorage()
06-22 07:43:43.293  5613  5613 E Zygote  : v2
06-22 07:43:43.293  5613  5613 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:43.293  5613  5613 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:43.293  5613  5613 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:43.293  5613  5613 I libpersona: KNOX_SDCARD checking this for 10023
06-22 07:43:43.293  5613  5613 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:43.303  1017  1389 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.303  1017  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.303  1017  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:43.303  1017  3035 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5613 uid=10023 gids={50023, 9997} abi=armeabi-v7a
06-22 07:43:43.303  1017  1389 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:43:43.313  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
06-22 07:43:43.313  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.313  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.313  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.313  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.323  5585  5612 D Compatibility: found: 2
06-22 07:43:43.323  5630  5630 E Zygote  : MountEmulatedStorage()
06-22 07:43:43.323  5630  5630 E Zygote  : v2
06-22 07:43:43.323  5630  5630 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:43.323  5630  5630 I libpersona: KNOX_SDCARD checking this for 10052
06-22 07:43:43.323  5630  5630 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:43.333  5630  5630 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:43.333  5630  5630 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-22 07:43:43.333  1017  1490 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5630 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
06-22 07:43:43.343  5585  5612 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
06-22 07:43:43.343  5585  5612 D Compatibility: skipping ResolveInfo{1a855030 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
06-22 07:43:43.343  5585  5612 D Compatibility: considering ResolveInfo{1e51f4a9 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
06-22 07:43:43.343  5585  5612 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
06-22 07:43:43.343  5613  5613 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:43.353  5613  5613 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:43.363  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:43:43.363  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
06-22 07:43:43.363  5585  5612 D Compatibility: enabling receiver ResolveInfo{526da2e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
06-22 07:43:43.363  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.363  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.363  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:43:43.373  5585  5612 D Compatibility: enabling receiver ResolveInfo{359919cf com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
06-22 07:43:43.373  5630  5630 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:43.383  5630  5630 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:43.383  5585  5612 D Compatibility: enabling receiver ResolveInfo{3d273f5c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
06-22 07:43:43.393  5585  5612 D Compatibility: enabling receiver ResolveInfo{1c2c3265 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
06-22 07:43:43.393  5585  5612 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
06-22 07:43:43.393  1017  1389 I ActivityManager: Killing 5119:com.sec.knox.bridge/1000 (adj 15): empty #21
06-22 07:43:43.403  3875  5607 W IcingInternalCorpora: getNumBytesRead when not calculated.
06-22 07:43:43.413  1017  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:43:43.413  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
06-22 07:43:43.413  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.413  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.413  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:43.443  5613  5613 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
06-22 07:43:43.443  1017  3035 I ActivityManager: Killing 5137:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #21
06-22 07:43:43.463  5319  5519 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
06-22 07:43:43.473  3875  5506 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
06-22 07:43:43.483  1017  1490 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
06-22 07:43:43.483  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
06-22 07:43:43.483  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.483  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.483  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
06-22 07:43:43.493  5200  5200 I Finsky  : [1] com.google.android.finsky.utils.bh.run(2302): Package state data is missing for com.test.thalitest
06-22 07:43:43.543  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
06-22 07:43:43.543  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
06-22 07:43:43.543  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
06-22 07:43:43.543  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
06-22 07:43:43.543  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
06-22 07:43:43.543  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
06-22 07:43:43.553  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
06-22 07:43:43.563  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
06-22 07:43:43.563  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
06-22 07:43:43.563  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
06-22 07:43:43.563  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
06-22 07:43:43.563  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
06-22 07:43:43.563  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-22 07:43:43.563  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
06-22 07:43:43.563  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.563  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.563  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
06-22 07:43:43.573  5613  5613 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
06-22 07:43:43.593  5569  5569 I art     : Rejecting re-init on previously-failed class java.lang.Class<jry>
06-22 07:43:43.613  5569  5569 I art     : Rejecting re-init on previously-failed class java.lang.Class<jry>
06-22 07:43:43.643  5569  5569 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
06-22 07:43:43.643  5569  5569 D CAR.SERVICE: onBind
06-22 07:43:43.643  5569  5569 D CAR.SERVICE: CSB onBind
06-22 07:43:43.643  5650  5650 D AndroidRuntime: 
06-22 07:43:43.643  5650  5650 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-22 07:43:43.653  5650  5650 D AndroidRuntime: CheckJNI is OFF
06-22 07:43:43.653  5650  5650 D AndroidRuntime: readGMSProperty: start
06-22 07:43:43.653  5650  5650 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:43:43.653  5650  5650 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:43:43.653  5650  5650 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:43:43.653  5650  5650 D AndroidRuntime: readGMSProperty: end
06-22 07:43:43.653  5650  5650 D AndroidRuntime: addProductProperty: start
06-22 07:43:43.663  5630  5652 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-22 07:43:43.703  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
06-22 07:43:43.703  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:43.703  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
06-22 07:43:43.703  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:43.703  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:43.713  1017  1389 I ActivityManager: Killing 5252:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
06-22 07:43:43.723  5569  5569 D CAR.TEL.Service: onBind, intent: Intent { cmp=com.google.android.gms/.car.CarCallService }
06-22 07:43:43.733  5569  5569 D CAR.TEL.Service: Creating a new CarCallService.
06-22 07:43:43.733  5569  5569 D CAR.TEL.Service: bindToInCallService
06-22 07:43:43.743  1017  1490 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
06-22 07:43:43.743  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
06-22 07:43:43.743  1017  1490 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
06-22 07:43:43.743  5569  5569 D CAR.SERVICE: onServiceConnected: ComponentInfo{com.google.android.gms/com.google.android.gms.car.CarCallService}, service: glo@16672a08
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
06-22 07:43:43.773  5569  5582 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
06-22 07:43:43.783  5569  5582 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
06-22 07:43:43.783  5569  5582 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
06-22 07:43:43.803  5650  5650 E AffinityControl: AffinityControl: registerfunction enter
06-22 07:43:43.803  5569  5582 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
06-22 07:43:43.803  5569  5582 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk': Failed to open oat filename for reading: No such file or directory
06-22 07:43:43.813  1017  3953 D LocationManagerService: getProviders()=[passive]
06-22 07:43:43.813  5569  5582 D ChimeraFileApk: Classloading successful. Optimized code found.
06-22 07:43:43.813  5569  5582 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
06-22 07:43:43.823  5650  5650 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-22 07:43:43.843  1017  1485 E PersonaManagerService: inState():  stateMachine is null !!
06-22 07:43:43.843  1017  1485 I PersonaManagerService: PersonaId don't exist
06-22 07:43:43.843  1017  1485 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-22 07:43:43.843  1017  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:43.863  1017  1485 W ActivityManager: mDVFSHelper.acquire()
06-22 07:43:43.863  1017  1485 D FocusedStackFrame: Set to : 0
06-22 07:43:43.873  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-22 07:43:43.873  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
06-22 07:43:43.873  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.873  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.873  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.873  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:43.893  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-22 07:43:43.893  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-22 07:43:43.893  1017  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-22 07:43:43.893  1017  1485 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5672 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:43:43.893  1017  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:43.893   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
06-22 07:43:43.903  5672  5672 E Zygote  : MountEmulatedStorage()
06-22 07:43:43.903  5672  5672 E Zygote  : v2
06-22 07:43:43.903  5672  5672 I libpersona: KNOX_SDCARD checking this for 10170
06-22 07:43:43.903  5672  5672 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:43.903  5672  5672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:43.903  5672  5672 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:43.913  5672  5672 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-22 07:43:43.913  5569  5582 D GoogleCertificatesImpl: Fetched 154 Google release certificates
06-22 07:43:43.923  1017  1485 D InputDispatcher: Focused application set to: xxxx
06-22 07:43:43.923  1017  1485 D InputDispatcher: Focus left window: 1474
06-22 07:43:43.923  5650  5650 D AndroidRuntime: Shutting down VM
06-22 07:43:43.933  5672  5672 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:43.933  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:43:43.933  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:43:43.933  5672  5672 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:43.933   305   305 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 12.923ms total 43.600ms
06-22 07:43:43.943  1017  1029 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-22 07:43:43.953  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:43:43.963   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 23.902ms
06-22 07:43:43.963  1017  1017 V ActivityManager: Display changed displayId=0
06-22 07:43:43.983   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 17.510ms
06-22 07:43:44.003  1017  1029 D PersonaManager: isKioskContainerExistOnDevice
06-22 07:43:44.003  5388  5388 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-22 07:43:44.013   257   798 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
06-22 07:43:44.013   257   451 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
06-22 07:43:44.023  1474  1474 V ActivityThread: updateVisibility : ActivityRecord{32a30566 token=android.os.BinderProxy@337d6359 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-22 07:43:44.023  1474  1474 D Launcher: onTrimMemory. Level: 20
06-22 07:43:44.033  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
06-22 07:43:44.043  5569  5582 D CAR.SERVICE: Package validated; name: com.android.vending
06-22 07:43:44.043  5569  5582 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
06-22 07:43:44.053  5481  5501 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-22 07:43:44.073  5481  5501 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-22 07:43:44.073  5481  5501 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:43:44.073  5481  5501 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-22 07:43:44.073  5388  5402 W art     : Suspending all threads took: 5.889ms
06-22 07:43:44.133  5650  5650 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,06-22 07:43:44.163  5672  5672 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,06-22 07:43:44.183  5672  5672 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1805-1807)
06-22 07:43:44.183  5672  5672 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-22 07:43:44.203  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-22 07:43:44.203  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:44.203  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:44.203  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,06-22 07:43:44.213  5672  5672 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c2c3265}
,06-22 07:43:44.213  5672  5672 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:44.213  5672  5672 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-22 07:43:44.253  5672  5672 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-22 07:43:44.253  5672  5672 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:43:44.253  5672  5672 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-22 07:43:44.263  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-22 07:43:44.263  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,06-22 07:43:44.273  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:44.273  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:44.273  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:43:44.273  1017  1218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,06-22 07:43:44.273  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:44.273  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.273  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.273  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:44.293  5706  5706 E Zygote  : MountEmulatedStorage()
,06-22 07:43:44.293  5706  5706 E Zygote  : v2
06-22 07:43:44.293  5706  5706 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:44.293  5706  5706 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:44.293  1017  1218 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5706 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:43:44.293  5706  5706 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:44.303  1017  1218 I ActivityManager: Killing 4896:com.google.android.talk/u0a102 (adj 15): empty #21
06-22 07:43:44.303  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
06-22 07:43:44.303  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,06-22 07:43:44.303  5672  5703 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-22 07:43:44.303  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:44.303  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:44.303  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
06-22 07:43:44.303  5706  5706 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:43:44.303  5706  5706 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:44.303  1017  1473 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
06-22 07:43:44.303  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,06-22 07:43:44.313  5388  5388 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,06-22 07:43:44.313  1824  1824 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:43:44.333  5630  5652 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 463 ms] updated apps [took 463 ms] 
,06-22 07:43:44.333  5672  5672 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-22 07:43:44.333  5672  5672 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-22 07:43:44.333  5672  5672 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,06-22 07:43:44.343  5672  5672 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-22 07:43:44.343  5672  5672 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-22 07:43:44.343  5672  5672 I Adreno-EGL: Build Date: 04/06/15 Mon
06-22 07:43:44.343  5672  5672 I Adreno-EGL: Local Branch: 
06-22 07:43:44.343  5672  5672 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-22 07:43:44.343  5672  5672 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-22 07:43:44.343  5672  5672 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-22 07:43:44.353  5706  5706 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:44.353  5388  5704 W AccountFeatureHelper: Write apps_features disabled false
,06-22 07:43:44.353  5706  5706 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:44.393  5706  5706 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,06-22 07:43:44.393  5706  5706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,06-22 07:43:44.393  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,06-22 07:43:44.403  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,06-22 07:43:44.403  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:44.403  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:44.403  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,06-22 07:43:44.403  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,06-22 07:43:44.403  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:44.403  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.403  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.403  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:44.423  5706  5706 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,06-22 07:43:44.423  3875  4343 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,06-22 07:43:44.433  5730  5730 E Zygote  : MountEmulatedStorage(),
06-22 07:43:44.433  5730  5730 I libpersona: KNOX_SDCARD checking this for 10098
06-22 07:43:44.433  5730  5730 E Zygote  : v2
06-22 07:43:44.433  5730  5730 I libpersona: KNOX_SDCARD not a persona,
06-22 07:43:44.433  5730  5730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:44.433  5706  5728 E FilterInstaller: installFilters,
06-22 07:43:44.433  5706  5728 E FilterInstaller: There is no requred permission,
,06-22 07:43:44.443  5730  5730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:43:44.443  5730  5730 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:44.443  1017  1490 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5730 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-22 07:43:44.443  1017  1390 I ActivityManager: Killing 5016:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,06-22 07:43:44.473  5730  5730 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:44.473  5730  5730 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:44.483  5672  5744 D BluetoothAdapter: 451150086: getState() :  mService = null. Returning STATE_OFF
,06-22 07:43:44.523  5730  5730 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
06-22 07:43:44.523  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{7d3672 u0 com.test.thalitest/.MainActivity t43}
,06-22 07:43:44.523  5730  5730 D PackageIntentReceiver: Not GearManger package! 
,06-22 07:43:44.523  1017  1473 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,06-22 07:43:44.523  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.523  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.523  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.523  1017  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:44.533  3875  4343 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,06-22 07:43:44.543  5757  5757 E Zygote  : MountEmulatedStorage()
,06-22 07:43:44.543  5757  5757 E Zygote  : v2
06-22 07:43:44.543  5757  5757 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:44.543  5757  5757 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:44.543  5757  5757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:44.543  1017  1473 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5757 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:43:44.543  5757  5757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:43:44.553  5757  5757 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:44.573  5757  5757 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:44.573  5757  5757 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:44.583  5672  5742 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,06-22 07:43:44.593  5388  5388 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,06-22 07:43:44.593  1017  1473 I ActivityManager: Killing 5062:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,06-22 07:43:44.613  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,06-22 07:43:44.613  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.613  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.613  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:44.613  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:44.633  5777  5777 E Zygote  : MountEmulatedStorage()
,06-22 07:43:44.633  5777  5777 E Zygote  : v2
06-22 07:43:44.633  5777  5777 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:44.633  5777  5777 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:44.633  1017  1029 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5777 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:43:44.633  5777  5777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:44.633  1017  1029 I ActivityManager: Killing 5172:com.samsung.android.sm/1000 (adj 15): empty #21
06-22 07:43:44.633  5777  5777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:44.633  5777  5777 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:44.653  5672  5672 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:43:44.663  5777  5777 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:44.663  5777  5777 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:44.673  5672  5672 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-22 07:43:44.683  5672  5672 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-22 07:43:44.683  5672  5672 D PhoneWindow: *FMB* installDecor flags : -2139027200
,06-22 07:43:44.683  5672  5672 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-22 07:43:44.693  5672  5672 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:44.693  5672  5672 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:43:44.693  1017  1390 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
06-22 07:43:44.693  1017  1390 I ActivityManager: Killing 5336:com.sec.pcw.device/1000 (adj 15): empty #21
06-22 07:43:44.693  5777  5794 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
,06-22 07:43:44.703  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:44.713  1017  1017 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:44.713  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:43:44.713  1017  1017 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
06-22 07:43:44.713  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,06-22 07:43:44.713  5777  5794 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,06-22 07:43:44.713  1017  1017 I BackgroundCompactionService: onStart. jobID=801
,06-22 07:43:44.713  1017  1017 I BackgroundCompactionService: onStart done. jobID=801
06-22 07:43:44.713  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:43:44.713  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
06-22 07:43:44.713  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:44.713  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:44.713  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,06-22 07:43:44.723  1017  5796 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,06-22 07:43:44.723  5777  5777 D AcmsService: Enter Oncreate
06-22 07:43:44.723  1017  5796 I BackgroundCompactionService: compact_memory command done
06-22 07:43:44.723  5777  5777 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:44.723  5777  5777 D AcmsService: creating AcmsCore
06-22 07:43:44.723  5777  5777 D AcmsCore: AcmsCore.getAcmsCore() - Enter
06-22 07:43:44.723  5777  5777 D AcmsCore: AcmsCore
,06-22 07:43:44.733  5777  5777 D AcmsCore: init
06-22 07:43:44.733  5777  5777 D AcmsCore: Looper handler is not null
06-22 07:43:44.733  5777  5777 D AcmsCore: Post to AcmsCoreHandler
06-22 07:43:44.733  5777  5777 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:44.733  5777  5777 D AcmsServiceMonitor: Incrementing - Counter value: 1
06-22 07:43:44.733  5777  5777 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,06-22 07:43:44.733  5777  5777 D AcmsService: onStartCommand
06-22 07:43:44.733  5777  5777 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
06-22 07:43:44.733  5777  5777 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
06-22 07:43:44.733  5777  5777 D AcmsServiceMonitor: Incrementing - Counter value: 2
06-22 07:43:44.733  5777  5777 D AcmsService: Incremented Counter Value : onStartCommand
,06-22 07:43:44.733  1017  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,06-22 07:43:44.733  5777  5799 D AcmsCertificateMngr: AcmsCertificateMngr
,06-22 07:43:44.733  5777  5777 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,06-22 07:43:44.753  5777  5799 D AcmsRevocationMngr: AcmsRevocationMngr
,06-22 07:43:44.763  5672  5801 D OpenGLRenderer: Render dirty regions requested: true
,06-22 07:43:44.773  5319  5319 I Mms/MmsApp:  start initViewCache mms
,06-22 07:43:44.773  5319  5319 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1928.058593
06-22 07:43:44.773  1017  1390 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,06-22 07:43:44.773  1017  1390 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-22 07:43:44.773  1017  1390 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-22 07:43:44.773  5319  5319 D Mms/ComposeMessageFragment: fillCache, easy = false
,06-22 07:43:44.783  5672  5672 V ActivityThread: updateVisibility : ActivityRecord{1111b38d token=android.os.BinderProxy@3d2fdcb7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-22 07:43:44.783  5672  5672 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,06-22 07:43:44.793  5672  5672 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,06-22 07:43:44.793   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,06-22 07:43:44.813  1017  1390 D InputDispatcher: Focus entered window: 5672
,06-22 07:43:44.823  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,06-22 07:43:44.823  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,06-22 07:43:44.823  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-22 07:43:44.823  5672  5672 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,06-22 07:43:44.823  5672  5801 I OpenGLRenderer: Initialized EGL, version 1.4
06-22 07:43:44.823  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-22 07:43:44.833  5672  5801 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
06-22 07:43:44.833  5672  5801 D OpenGLRenderer: Enabling debug mode 0
,06-22 07:43:44.853  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-22 07:43:44.863  1017  5804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:43:44.863  1177  1177 I StatusBar: Icon Only
,06-22 07:43:44.863  1177  1177 D PanelView: There is/are notification(s) 
06-22 07:43:44.863  5777  5777 D AcmsService: Inside handle Intent
06-22 07:43:44.863  5777  5777 D AcmsService: App added - package name: com.test.thalitest
06-22 07:43:44.863  5777  5777 D AcmsCore: Post to AcmsCoreHandler
06-22 07:43:44.863  5777  5777 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:44.863  5777  5777 D AcmsServiceMonitor: Incrementing - Counter value: 3
06-22 07:43:44.863  5777  5777 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
06-22 07:43:44.863  5777  5777 D AcmsService: Decremented Counter Value : handleStartIntent
06-22 07:43:44.863  5777  5777 D AcmsServiceMonitor: Decrementing - Counter value: 2
,06-22 07:43:44.873  5672  5672 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-22 07:43:44.873  5672  5672 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d2fdcb7 time:72498
,06-22 07:43:44.903  5319  5319 D AbsListView: Get MotionRecognitionManager
,06-22 07:43:44.903  1017  1136 D MotionRecognitionService:  ssp status : false
,06-22 07:43:44.913  5319  5319 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 136.390416
,06-22 07:43:44.913  1017  1047 I ActivityManager: Displayed Component not be shown by security: +893ms (total +1s45ms)
,06-22 07:43:44.913  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7d3672 u0 com.test.thalitest/.MainActivity t43} time:72534
06-22 07:43:44.913  1017  1047 W ActivityManager: mDVFSHelper.release()
,06-22 07:43:44.933   257   798 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
06-22 07:43:44.933   257   451 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
06-22 07:43:44.943  1842  1842 I SamsungIME: getCurrentCandidateView
06-22 07:43:44.973  1017  2637 D SSRM:n  : SIOP:: AP = 380
06-22 07:43:44.973  1017  1512 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
06-22 07:43:44.973  1017  1512 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
06-22 07:43:44.973  1824  1824 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:43:44.983  5672  5672 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5672
06-22 07:43:45.033  5319  5319 D Mms/BubbleViewCache: fillCache bubble = 1
06-22 07:43:45.033  1017  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:43:45.043  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.043  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.043  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
06-22 07:43:45.053   277   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-22 07:43:45.053   277   989 D Netd    : getNetworkForDns: using netid 0 for uid 10026
06-22 07:43:45.053  1842  1842 D SamsungIME: Dismiss ExpandCandiate
06-22 07:43:45.053  5200  5200 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
06-22 07:43:45.063  1017  1029 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
06-22 07:43:45.063  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
06-22 07:43:45.063  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.063  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.063  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
06-22 07:43:45.073  5200  5200 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
06-22 07:43:45.073  1017  1096 V AlarmManager: waitForAlarm result :4
06-22 07:43:45.083  1017  1512 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:43:45.083  1017  1512 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.083  1017  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.083  1017  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
06-22 07:43:45.093  5200  5200 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
06-22 07:43:45.113  5200  5200 W InstanceID/Rpc: Found 10011
06-22 07:43:45.113  5200  5200 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 9 minutes (failures=1)
06-22 07:43:45.133  1017  1390 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
06-22 07:43:45.133  1017  1390 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
06-22 07:43:45.133  1017  1390 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.133  1017  1390 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.133  1017  1390 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
06-22 07:43:45.143  1017  3953 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:43:45.143  1017  3953 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.143  1017  3953 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.143  1017  3953 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
06-22 07:43:45.143  1824  1824 D WearableService: callingUid 10011, callindPid: 1824
06-22 07:43:45.153  1017  3035 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.153  1017  3035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.153  1017  3035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
06-22 07:43:45.173  5672  5672 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-22 07:43:45.183  1824  2073 D DeviceConnectionService: client connected with version: 8486000
06-22 07:43:45.203  5200  5811 I Finsky  : [926] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
06-22 07:43:45.223  1017  1389 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:43:45.223  1017  1389 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.223  1017  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.223  1017  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:45.223  5200  5243 I PlayCommon: [913] com.google.android.play.a.w.a(27551): Starting to flush logs
06-22 07:43:45.233  5200  5200 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
06-22 07:43:45.233  5200  5200 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
06-22 07:43:45.243  1017  3035 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
06-22 07:43:45.253  1017  3035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
06-22 07:43:45.253  1824  1824 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:43:45.263  1842  1842 I SamsungIME: getDebugLevel  : 0x4f4c
06-22 07:43:45.273  5200  5243 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-22 07:43:45.273   277   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-22 07:43:45.273   277   989 D Netd    : getNetworkForDns: using netid 0 for uid 10026
06-22 07:43:45.283  5200  5243 I PlayCommon: [913] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
06-22 07:43:45.293  5672  5806 D jxcore_app_log: JniHelper::setJavaVM(0xb8b312f0), pthread_self() = -1190609600
06-22 07:43:45.303  1842  1842 I SamsungIME: getDebugLevel  : 0x4f4c
06-22 07:43:45.303  5672  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:43:45.303  5672  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:43:45.303  5672  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:43:45.303  5672  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:43:45.303  5672  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:43:45.303  5672  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a399fd added. We now have 1 listener(s)
06-22 07:43:45.313  1017  1485 I ActivityManager: Killing 5085:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
06-22 07:43:45.313  1017  1485 I ActivityManager: Killing 5154:com.google.android.apps.plus/u0a117 (adj 15): empty #22
06-22 07:43:45.313  1842  1842 I SamsungIME: KeybaordView init() : load resources
06-22 07:43:45.313  5672  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
06-22 07:43:45.313  5672  5806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
06-22 07:43:45.313  5672  5806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:43:45.323  5672  5806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:43:45.323  5672  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4ed3c0 added. We now have 1 listener(s)
06-22 07:43:45.323  5672  5806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-22 07:43:45.333  5672  5806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:45.333  5672  5806 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-22 07:43:45.333  5672  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:43:45.333  5672  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:43:45.333  5672  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:43:45.333  5672  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-22 07:43:45.333  5672  5806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:43:45.333  5672  5806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
06-22 07:43:45.333  3875  4343 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
06-22 07:43:45.343  5672  5806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:43:45.343  5672  5806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:43:45.343  5672  5806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:43:45.343  5672  5806 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:43:45.343  5672  5806 I io.jxcore.node.LifeCycleMonitor: start: OK
06-22 07:43:45.353  1842  1842 I SamsungIME: getCurrentKeyboard
06-22 07:43:45.353  1842  1842 I SamsungIME: getTextKeyboard
06-22 07:43:45.373  5672  5672 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-22 07:43:45.413  1842  1842 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
06-22 07:43:45.513  3875  4343 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
06-22 07:43:45.533  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-22 07:43:45.533  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:45.533  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:45.533  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:43:45.903  5672  5815 W jxcore-log: Initializing JXcore engine
06-22 07:43:45.903  5672  5815 W jxcore-log: JXcore engine is ready
,06-22 07:43:45.953  1902  1902 E audit   : type=1400 msg=audit(1466574225.953:203): avc:  denied  { ioctl } for  pid=5815 comm="Thread-1018" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-22 07:43:45.953  1902  1902 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:45.953  1902  1902 E audit   : type=1300 msg=audit(1466574225.953:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f3008f8 items=0 ppid=305 ppcomm=main pid=5815 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1018" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-22 07:43:45.953  1902  1902 E audit   : type=1320 msg=audit(1466574225.953:203): 
,06-22 07:43:45.973  5672  5815 W jxcore-log: Starting JXcore engine
,06-22 07:43:46.073  5672  5815 W jxcore-log: Platform android
06-22 07:43:46.073  5672  5815 W jxcore-log: 
06-22 07:43:46.073  5672  5815 W jxcore-log: Process ARCH arm
06-22 07:43:46.073  5672  5815 W jxcore-log: 
,06-22 07:43:46.133   287   287 E SMD     : DCD OFF
,06-22 07:43:46.273  5672  5815 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:43:46.273  5672  5815 I jxcore-log: 
,06-22 07:43:46.273  5672  5815 W jxcore-log: JXcore engine is started
,06-22 07:43:46.283  5672  5806 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:43:46.283  5672  5672 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-22 07:43:46.293  5672  5815 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-22 07:43:46.293  5672  5815 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-22 07:43:46.303  5672  5672 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,06-22 07:43:46.303  5672  5672 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-22 07:43:46.313  1017  1473 D FocusedStackFrame: Set to : 0
06-22 07:43:46.313  1017  1473 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:46.313  1017  1473 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-22 07:43:46.313  1017  1473 D InputDispatcher: Focused application set to: xxxx
06-22 07:43:46.313  1017  1473 D InputDispatcher: Focus left window: 5672
06-22 07:43:46.323  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:43:46.323  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:43:46.323  1017  1473 I ActivityManager: Killing 5354:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,06-22 07:43:46.333  5672  5806 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,06-22 07:43:46.333  5672  5672 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,06-22 07:43:46.333  5672  5672 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,06-22 07:43:46.333  5672  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-22 07:43:46.333  5672  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-22 07:43:46.333  5672  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-22 07:43:46.333  5672  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-22 07:43:46.333  5672  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a399fd removed from the list
06-22 07:43:46.333  5672  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-22 07:43:46.333  5672  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4ed3c0 removed from the list
06-22 07:43:46.333  5672  5672 D io.jxcore.node.ConnectivityMonitor: stop
06-22 07:43:46.333  5672  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,06-22 07:43:46.333  5672  5672 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-22 07:43:46.343   257   798 I SurfaceFlinger: id=12 Removed NainActivit (6/8),
06-22 07:43:46.343   257   447 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,06-22 07:43:46.353  1017  1490 W ActivityManager: mDVFSHelper.acquire()
,06-22 07:43:46.353  1017  1490 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,06-22 07:43:46.373  1474  1474 D Launcher: onRestart, Launcher: 917671905
,06-22 07:43:46.383  1474  1474 D Launcher: onStart, Launcher: 917671905
,06-22 07:43:46.383  1474  1474 D Launcher.HomeView: onStart
,06-22 07:43:46.383  1474  1474 D Launcher: onResume, Launcher: 917671905
,06-22 07:43:46.383  1017  1473 D SettingsProvider: name = kids_home_mode
06-22 07:43:46.383  1017  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-22 07:43:46.383  1017  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-22 07:43:46.383  1017  1473 D SettingsProvider: selectionArgs: false
06-22 07:43:46.383  1017  1473 D SettingsProvider: selectionArgs: 10006
06-22 07:43:46.383  1017  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-22 07:43:46.383  1017  1473 D SettingsProvider: ret = -1
,06-22 07:43:46.383  1474  1474 D Launcher.HomeView: onResume
,06-22 07:43:46.393  1474  1474 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,06-22 07:43:46.393  1474  1474 D MenuAppsGridFragment: onResume
,06-22 07:43:46.403  1474  1474 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
,06-22 07:43:46.403  1474  1474 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,06-22 07:43:46.413  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:46.413  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.413  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,06-22 07:43:46.413  1017  1490 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,06-22 07:43:46.413  1017  1490 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,06-22 07:43:46.413  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:46.413  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.413  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
06-22 07:43:46.413  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,06-22 07:43:46.413  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0,
06-22 07:43:46.413  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.413  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.413  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:46.433  5820  5820 E Zygote  : MountEmulatedStorage(),
,06-22 07:43:46.433  5820  5820 E Zygote  : v2,
06-22 07:43:46.433  5820  5820 I libpersona: KNOX_SDCARD checking this for 10039
06-22 07:43:46.433  5820  5820 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:46.433  1017  1030 D ActivityManager: handle home activity for 0,
06-22 07:43:46.433  1017  1490 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=5820 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,06-22 07:43:46.433  1017  1030 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
06-22 07:43:46.433  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
06-22 07:43:46.433  1017  1030 D KnoxTimeoutHandler: post home show event for user 0
06-22 07:43:46.433  1017  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-22 07:43:46.433  1017  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-22 07:43:46.433  1017  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-22 07:43:46.433  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
06-22 07:43:46.433  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
06-22 07:43:46.433  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-22 07:43:46.433  1474  1474 D Launcher.HomeView: onPause
06-22 07:43:46.443  1474  1474 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,06-22 07:43:46.443  5820  5820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:46.443  5820  5820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:46.443  5820  5820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:46.453  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.453  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.453  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,06-22 07:43:46.463  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.463  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
06-22 07:43:46.463  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.463  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,06-22 07:43:46.463  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.463  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.463  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.463  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:46.463  5820  5820 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:46.473  5820  5820 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:46.483  5835  5835 E Zygote  : MountEmulatedStorage(),
06-22 07:43:46.483  5835  5835 E Zygote  : v2
06-22 07:43:46.483  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5835 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
06-22 07:43:46.483  5835  5835 I libpersona: KNOX_SDCARD checking this for 10089
06-22 07:43:46.483  5835  5835 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:46.483  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.483  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.483  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
06-22 07:43:46.483  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,06-22 07:43:46.483  5835  5835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:46.483  5835  5835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-22 07:43:46.483  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
06-22 07:43:46.483  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.483  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.483  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:46.483  5835  5835 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,06-22 07:43:46.503  5846  5846 E Zygote  : MountEmulatedStorage(),
06-22 07:43:46.503  5846  5846 E Zygote  : v2
,06-22 07:43:46.503  5846  5846 I libpersona: KNOX_SDCARD checking this for 10139
06-22 07:43:46.503  5846  5846 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:46.503  5846  5846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
06-22 07:43:46.503  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5846 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
,06-22 07:43:46.513  5846  5846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:46.513  5835  5835 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:46.513  5835  5835 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:46.513  5846  5846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:46.523  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.523  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.523  1017  1029 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1474, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
06-22 07:43:46.523  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,06-22 07:43:46.533  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.533  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.533  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,06-22 07:43:46.533  2444  2444 D Recents_RecreateReceiver: onReceive by home
,06-22 07:43:46.533  1017  3953 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.533  1017  3953 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.533  1017  3953 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
06-22 07:43:46.533  1017  3953 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,06-22 07:43:46.533   257   257 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,06-22 07:43:46.543  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.543  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.543  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.543  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-22 07:43:46.543  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.,
06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-22 07:43:46.543  5820  5820 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
06-22 07:43:46.553  1017  1512 D InputDispatcher: Focus entered window: 1474
06-22 07:43:46.543  5835  5835 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-22 07:43:46.553  5835  5835 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
06-22 07:43:46.553  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-22 07:43:46.553  1474  1474 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-22 07:43:46.553  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-22 07:43:46.553  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-22 07:43:46.563  5864  5864 E Zygote  : MountEmulatedStorage(),
06-22 07:43:46.563  1017  3953 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5864 uid=10084 gids={50084, 9997} abi=armeabi-v7a
06-22 07:43:46.563  5864  5864 E Zygote  : v2
06-22 07:43:46.563  5864  5864 I libpersona: KNOX_SDCARD checking this for 10084
06-22 07:43:46.563  5864  5864 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:46.563  5864  5864 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-22 07:43:46.573  1474  1474 V ActivityThread: updateVisibility : ActivityRecord{32a30566 token=android.os.BinderProxy@337d6359 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
06-22 07:43:46.573  1474  1474 D Launcher.HomeView: onStop
06-22 07:43:46.573  1017  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-22 07:43:46.573  5864  5864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-22 07:43:46.583  1017  5870 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:43:46.583  5846  5846 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:46.583  5846  5846 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:46.583  1177  1177 I StatusBar: Icon Only
06-22 07:43:46.583  1177  1177 D PanelView: There is/are notification(s) 
06-22 07:43:46.593  5864  5864 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
06-22 07:43:46.593  5672  5672 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,06-22 07:43:46.603  5864  5864 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:46.603  5864  5864 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:46.613  1474  1474 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@337d6359 time:74234
,06-22 07:43:46.613  1842  1842 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-22 07:43:46.623  5817  5817 D AndroidRuntime: 
06-22 07:43:46.623  5817  5817 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,06-22 07:43:46.633  5817  5817 D AndroidRuntime: CheckJNI is OFF
,06-22 07:43:46.633  5817  5817 D AndroidRuntime: readGMSProperty: start
06-22 07:43:46.633  5817  5817 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:43:46.633  5817  5817 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:43:46.633  5817  5817 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:43:46.633  5817  5817 D AndroidRuntime: readGMSProperty: end
06-22 07:43:46.633  5817  5817 D AndroidRuntime: addProductProperty: start
,06-22 07:43:46.633  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,06-22 07:43:46.643  1017  1047 W ActivityManager: mDVFSHelper.release()
,06-22 07:43:46.643  5864  5864 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:43:46.643  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{193e804d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:74262
,06-22 07:43:46.663  1017  3035 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:46.663  1017  3035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.663  1017  3035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
06-22 07:43:46.663  1017  3035 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,06-22 07:43:46.663  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:46.663  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.663  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:46.663  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:46.663  5846  5846 V TaskCloserActivity: TaskCloserActivity enter()
,06-22 07:43:46.673  5846  5846 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,06-22 07:43:46.683  1017  3035 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5891 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,06-22 07:43:46.683  1017  3035 I ActivityManager: Killing 5370:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,06-22 07:43:46.683  1017  1512 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:46.683  1017  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:46.683  1017  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone,
,06-22 07:43:46.693  1017  1512 I ActivityManager: Killing 5403:com.sec.spp.push/u0a32 (adj 15): empty #21
06-22 07:43:46.693  5891  5891 E Zygote  : MountEmulatedStorage()
06-22 07:43:46.693  5891  5891 E Zygote  : v2
06-22 07:43:46.693  5891  5891 I libpersona: KNOX_SDCARD checking this for 10135
06-22 07:43:46.693  5891  5891 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:46.693  5891  5891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:46.693  5891  5891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:43:46.693  5891  5891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:46.723  1017  1473 I ActivityManager: Killing 5420:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,06-22 07:43:46.733  5891  5891 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:46.733  5891  5891 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:46.753  5891  5891 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
06-22 07:43:46.753  5891  5891 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-22 07:43:46.753  5891  5891 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
06-22 07:43:46.753  5891  5891 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
06-22 07:43:46.753  5891  5891 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-22 07:43:46.773  1017  1029 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:43:46.793  5817  5817 E AffinityControl: AffinityControl: registerfunction enter
,06-22 07:43:46.813  1017  1136 I ActivityManager: Killing 5436:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,06-22 07:43:46.823  5817  5817 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,06-22 07:43:46.833  1017  1389 D PackageManager: START PACKAGE DELETE: observer{436638812}
06-22 07:43:46.833  1017  1389 D PackageManager: pkg{<packageName>}
06-22 07:43:46.833  1017  1389 D PackageManager: user{0}
06-22 07:43:46.833  1017  1389 D PackageManager: caller{2000}
06-22 07:43:46.833  1017  1389 D PackageManager: flags{2}
,06-22 07:43:46.833  1017  1389 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,06-22 07:43:46.833  1017  1389 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,06-22 07:43:46.833  1017  1389 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-22 07:43:46.833  1017  1389 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,06-22 07:43:46.833  1017  1389 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,06-22 07:43:46.833  1017  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,06-22 07:43:46.833  1017  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,06-22 07:43:46.833  1017  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,06-22 07:43:46.833  1017  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
,06-22 07:43:46.833  1017  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,06-22 07:43:46.853  1017  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,06-22 07:43:46.853  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,06-22 07:43:46.853  1017  1042 I ActivityManager: Killing 5672:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,06-22 07:43:46.863  5820  5820 D NearbySource: Nearby Source Create!
,06-22 07:43:46.863  5820  5820 D NearbyContext: Nearby Context Create!
,06-22 07:43:46.903   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
06-22 07:43:46.903   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:46.903  5820  5820 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,06-22 07:43:46.903  5820  5820 D SLinkSource: Samsung link source created
,06-22 07:43:46.913  5777  5799 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,06-22 07:43:46.933  5777  5799 I AcmsKeyStoreHelper: Key Store exist
,06-22 07:43:46.933  5777  5799 I AcmsKeyStoreHelper: Hence loading the keystore file
,06-22 07:43:46.953  1017  1055 W PackageSettings: Skipping PackageSetting{1145a608 com.example.hello/10168} due to missing metadata
,06-22 07:43:47.003  1017  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,06-22 07:43:47.013  1017  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,06-22 07:43:47.063  1842  1842 E SamsungIME: mOCRHelper is null
,06-22 07:43:47.073  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,06-22 07:43:47.073  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,06-22 07:43:47.073  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-22 07:43:47.073  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
06-22 07:43:47.073  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,06-22 07:43:47.073  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,06-22 07:43:47.083  5777  5799 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
06-22 07:43:47.083  5777  5799 I AcmsCertificateMngr: getKeyStoreForApplication success 
06-22 07:43:47.083  5777  5799 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
06-22 07:43:47.083  5777  5799 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:47.083  5777  5799 D AcmsServiceMonitor: Decrementing - Counter value: 1
06-22 07:43:47.083  5777  5799 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,06-22 07:43:47.093  5777  5799 D AcmsCore: This is NOT a valid MirrorLink app
06-22 07:43:47.093  5777  5799 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
06-22 07:43:47.093  5777  5799 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:47.093  5777  5799 D AcmsServiceMonitor: Decrementing - Counter value: 0
06-22 07:43:47.093  5777  5799 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,06-22 07:43:47.093  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,06-22 07:43:47.113  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-22 07:43:47.113  5777  5777 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,06-22 07:43:47.123  5777  5777 D AcmsService: Enter onDestroy
06-22 07:43:47.123  5777  5777 I AcmsService: cleanUp(): inside service clean up
06-22 07:43:47.123  5777  5777 D AcmsCore: AcmsCore: inside DeInit
06-22 07:43:47.123  5777  5777 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
06-22 07:43:47.123  5777  5777 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
06-22 07:43:47.123  5777  5777 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
06-22 07:43:47.123  5777  5777 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
06-22 07:43:47.123  5777  5777 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,06-22 07:43:47.123  5777  5777 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
06-22 07:43:47.123  5777  5777 D AcmsService: killing acms process
06-22 07:43:47.123  5777  5777 I Process : Sending signal. PID: 5777 SIG: 9
,06-22 07:43:47.133  1429  1429 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:43:47.143  1429  1429 D RegisteredServicesCache: empty dynamic service
,06-22 07:43:47.143  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
06-22 07:43:47.143  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,06-22 07:43:47.143  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,06-22 07:43:47.143  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,06-22 07:43:47.153  1017  1123 V NetworkStats: performPollLocked() took 14ms
,06-22 07:43:47.153  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,06-22 07:43:47.163   277   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-22 07:43:47.163   277   989 D Netd    : getNetworkForDns: using netid 0 for uid 1000
06-22 07:43:47.163   277   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-22 07:43:47.163   277   989 D Netd    : getNetworkForDns: using netid 0 for uid 1000
06-22 07:43:47.163  1017  1124 D NtpTrustedTime: forceRefresh Fail.
06-22 07:43:47.173  1429  1429 D RegisteredComponentCache: Collect Tech packages for Knox
06-22 07:43:47.173  1017  1390 I ActivityManager: Process ACMS.Process (pid 5777)(adj 0) has died(58,772)
06-22 07:43:47.173  1429  1429 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:43:47.273  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,06-22 07:43:47.273  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicy: uID is 10170
06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-22 07:43:47.273  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-22 07:43:47.283  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-22 07:43:47.283  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,06-22 07:43:47.283  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,06-22 07:43:47.283  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=43_task.xml
,06-22 07:43:47.303  1017  1490 I art     : Explicit concurrent mark sweep GC freed 49497(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 4.944ms total 243.212ms
,06-22 07:43:47.303  1017  1055 I art     : WaitForGcToComplete blocked for 192.932ms for cause Explicit
,06-22 07:43:47.313  1017  1136 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-22 07:43:47.313  1017  1136 D SecContentProvider2: mCursor = null
,06-22 07:43:47.313  1824  2039 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicy: uID is 10170
06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
,06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,06-22 07:43:47.323  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-22 07:43:47.343  1017  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-22 07:43:47.343  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
06-22 07:43:47.343  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,06-22 07:43:47.343  1017  1041 W TextServicesManagerService: no available spell checker services found
,06-22 07:43:47.343  1017  2637 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,06-22 07:43:47.363  1017  1389 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-22 07:43:47.363  5820  5820 D GalleryCacheReady: Receive : home resume
,06-22 07:43:47.363  1017  3035 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:47.363  1017  3035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-22 07:43:47.363  1017  3035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,06-22 07:43:47.363  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.373  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.373  5319  5319 D Mms/UIEventReceiver: ui event
,06-22 07:43:47.373  1017  1473 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,06-22 07:43:47.373  5820  5910 D ContactProvider: getAllContactInfoList Start
,06-22 07:43:47.383  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:43:47.383  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-22 07:43:47.383  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,06-22 07:43:47.383  5846  5846 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,06-22 07:43:47.383  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.393  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.403  3569  3569 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jun 22 07:43:47 GMT+02:00 2016
,06-22 07:43:47.403  1017  1389 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
06-22 07:43:47.403  1017  1389 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,06-22 07:43:47.403  1017  1389 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:47.403  1017  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:47.403  1017  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-22 07:43:47.413  3569  3569 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,06-22 07:43:47.413  1017  1029 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
06-22 07:43:47.413  1017  1029 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,06-22 07:43:47.413  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,06-22 07:43:47.413  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.413  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.413  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.413  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.423  5916  5916 E Zygote  : MountEmulatedStorage()
,06-22 07:43:47.423  5916  5916 I libpersona: KNOX_SDCARD checking this for 10090
06-22 07:43:47.423  5916  5916 E Zygote  : v2
06-22 07:43:47.423  5916  5916 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:47.423  5916  5916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:47.433  5916  5916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-22 07:43:47.433  1017  1029 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5916 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,06-22 07:43:47.433  5916  5916 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.443  1017  2653 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
06-22 07:43:47.443  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,06-22 07:43:47.443  5319  5319 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,06-22 07:43:47.443  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.443  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.443  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.443  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.453  3569  3569 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,06-22 07:43:47.463  3569  3569 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-22 07:43:47.463  3569  3569 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,06-22 07:43:47.463  3569  5915 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,06-22 07:43:47.463  3569  5915 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
06-22 07:43:47.463  5925  5925 E Zygote  : MountEmulatedStorage()
06-22 07:43:47.463  5925  5925 E Zygote  : v2
06-22 07:43:47.463  5925  5925 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:47.463  5925  5925 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.463  5925  5925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:47.473  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:43:47.473  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
06-22 07:43:47.473  3569  5915 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,06-22 07:43:47.473  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.473  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.473  3569  5915 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
06-22 07:43:47.473  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.473  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.473  5925  5925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:43:47.483  5925  5925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.493  5916  5916 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.493  5916  5916 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.503   305   305 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 34.956ms
,06-22 07:43:47.523   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 16.522ms
06-22 07:43:47.523  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:43:47.523  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,06-22 07:43:47.533  5925  5925 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.533  5925  5925 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.533  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.533  1017  1055 I art     : Explicit concurrent mark sweep GC freed 13308(854KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 6.921ms total 223.726ms
,06-22 07:43:47.543   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 642us total 17.937ms
,06-22 07:43:47.543  3569  5915 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,06-22 07:43:47.553  3569  5915 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,06-22 07:43:47.553  3569  5915 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,06-22 07:43:47.553  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.563  5946  5946 E Zygote  : MountEmulatedStorage()
,06-22 07:43:47.563  5946  5946 E Zygote  : v2
06-22 07:43:47.563  5946  5946 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:47.563  5946  5946 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:47.563  5946  5946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:47.563  1017  1055 D PackageManager: delete codoeFile: 
,06-22 07:43:47.563  5946  5946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-22 07:43:47.563  1017  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
06-22 07:43:47.563  1017  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
06-22 07:43:47.563  5946  5946 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:47.563  1017  1055 D PackageManager: result of delete: 1{436638812}
06-22 07:43:47.573  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:43:47.573  1017  1389 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
06-22 07:43:47.573  1017  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
06-22 07:43:47.573  5817  5817 D AndroidRuntime: Shutting down VM
,06-22 07:43:47.573  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.573  1017  1389 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:47.573  1017  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:47.573  1017  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,06-22 07:43:47.573  1017  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-22 07:43:47.573  1017  1055 D PackageManager: userId{-1}
06-22 07:43:47.573  1017  1055 D PackageManager: andCode{true}
,06-22 07:43:47.583  5319  5955 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,06-22 07:43:47.583  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-22 07:43:47.583  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:43:47.583  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:43:47.583  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.583  5319  5955 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,06-22 07:43:47.583  3569  3569 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
06-22 07:43:47.583  1017  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
06-22 07:43:47.583  5946  5946 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.593  5946  5946 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.593  1017  1218 I TactileAssist: enable value -1
06-22 07:43:47.593  1017  1218 I TactileAssist: internal enable value -1
06-22 07:43:47.593  1017  1218 I TactileAssist: intensity value -1
06-22 07:43:47.593  1017  1218 I TactileAssist: saveAppList value true
,06-22 07:43:47.613  1017  1218 I TactileAssist: List of disabled apps :
,06-22 07:43:47.623  5916  5916 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-22 07:43:47.623  5916  5916 D elm:15121: ELMEngine.ELMEngine( context ).
,06-22 07:43:47.623  5916  5916 D elm:15121: MDMBridge.setEnterpriseBridge()
06-22 07:43:47.623  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.623  1017  1473 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,06-22 07:43:47.623  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,06-22 07:43:47.623  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:47.623  1017  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:47.623  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,06-22 07:43:47.623  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:43:47.633  5916  5916 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,06-22 07:43:47.633  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.633  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-22 07:43:47.633  3235  3235 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,06-22 07:43:47.633  3235  3235 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-22 07:43:47.633  3235  3235 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
06-22 07:43:47.633  3235  3235 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-22 07:43:47.633  3235  3235 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-22 07:43:47.633  3235  3235 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-22 07:43:47.633  3235  3235 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-22 07:43:47.633  3235  3235 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:47.633  3235  3235 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:43:47.633  3235  3235 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:43:47.633  3235  3235 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:43:47.633  3235  3235 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:47.633  3235  3235 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:43:47.633  3235  3235 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,06-22 07:43:47.633  5820  5910 D ContactProvider: getAllContactInfoList End
06-22 07:43:47.633  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.633  5946  5946 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
06-22 07:43:47.633  5820  5910 I syncContacts: thread: 1023, sync time = 571
06-22 07:43:47.643  5916  5916 D elm:15121: ElmAgentService : onCreate()
06-22 07:43:47.643  5916  5962 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,06-22 07:43:47.643  5916  5962 D elm:15121: MainReceiver.listeningToPackageRemoved()
06-22 07:43:47.643  5916  5962 D elm:15121: MDMBridge.getInstance()
06-22 07:43:47.643  5916  5962 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,06-22 07:43:47.643  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.643  5585  5585 D Compatibility: onReceive() it will make start service
06-22 07:43:47.643  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-22 07:43:47.643  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.643  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-22 07:43:47.643  5916  5962 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,06-22 07:43:47.653  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:43:47.653  1017  1485 D SecContentProvider2: uri = -1 selection = getSealedState
,06-22 07:43:47.653  1017  1485 D SecContentProvider2: mCursor = null
06-22 07:43:47.653  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,06-22 07:43:47.653  5946  5946 I PopupuiReceiver_KNOX: getSealedState : true
,06-22 07:43:47.653  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.653  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.653  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.653  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.653  1017  3035 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
06-22 07:43:47.653  1017  3035 D SecContentProvider2: mCursor = null
,06-22 07:43:47.653  5946  5946 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,06-22 07:43:47.653  1017  3953 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState,
06-22 07:43:47.653  1017  3953 D SecContentProvider2: mCursor = null
,06-22 07:43:47.653  5946  5946 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
06-22 07:43:47.653  5946  5946 D PopupuiReceiver: Action package removed
,06-22 07:43:47.663  5964  5964 E Zygote  : MountEmulatedStorage()
,06-22 07:43:47.663  5964  5964 E Zygote  : v2
06-22 07:43:47.663  5964  5964 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:47.663  5964  5964 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.663  5964  5964 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:47.663  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:43:47.673  5964  5964 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-22 07:43:47.673  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,06-22 07:43:47.673  5964  5964 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:47.673  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.673  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.673  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.673  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.683  5964  5964 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.683  5964  5964 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.693  5978  5978 E Zygote  : MountEmulatedStorage(),
06-22 07:43:47.693  5978  5978 I libpersona: KNOX_SDCARD checking this for 10145
06-22 07:43:47.693  5978  5978 E Zygote  : v2
06-22 07:43:47.693  5978  5978 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:47.693  5978  5978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-22 07:43:47.693  1017  1136 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5978 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:43:47.693  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
06-22 07:43:47.693  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,06-22 07:43:47.693  1017  1490 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
06-22 07:43:47.693  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,06-22 07:43:47.693  5978  5978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:47.693  1017  1490 W ActivityManager: userId = 0, bbcId = -10000,
06-22 07:43:47.693  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:47.693  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
06-22 07:43:47.703  5916  5916 D elm:15121: ElmAgentService : onDestroy().
,06-22 07:43:47.703  5978  5978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:47.703  5585  5985 D Compatibility: onHandleIntent()
06-22 07:43:47.703  5585  5985 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,06-22 07:43:47.703  5585  5985 D Compatibility: found: 2
06-22 07:43:47.703  5585  5985 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
06-22 07:43:47.703  5585  5985 D Compatibility: skipping ResolveInfo{2296f548 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
06-22 07:43:47.703  5585  5985 D Compatibility: considering ResolveInfo{36b28fe1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
06-22 07:43:47.703  5585  5985 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,06-22 07:43:47.713  5585  5985 D Compatibility: enabling receiver ResolveInfo{1ae40106 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,06-22 07:43:47.713  1017  1473 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-22 07:43:47.713  1017  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
06-22 07:43:47.713  5925  5925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,06-22 07:43:47.713  1017  1473 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:47.713  1017  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:47.713  1017  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,06-22 07:43:47.713  5585  5985 D Compatibility: enabling receiver ResolveInfo{3c0873c7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,06-22 07:43:47.723  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
06-22 07:43:47.723  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,06-22 07:43:47.723  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:47.723  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:47.723  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,06-22 07:43:47.723  5585  5985 D Compatibility: enabling receiver ResolveInfo{35ca1df4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
06-22 07:43:47.723  1017  1389 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,06-22 07:43:47.723  5964  5964 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
06-22 07:43:47.723  5964  5964 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
06-22 07:43:47.723  5964  5964 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,06-22 07:43:47.733  5978  5978 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:47.733  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.733  5978  5978 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:47.733  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.733  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.733  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.733  5630  5991 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-22 07:43:47.733  5585  5985 D Compatibility: enabling receiver ResolveInfo{1ae7491d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,06-22 07:43:47.743  5997  5997 E Zygote  : MountEmulatedStorage()
06-22 07:43:47.743  5997  5997 E Zygote  : v2,
06-22 07:43:47.743  5585  5985 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
06-22 07:43:47.743  5997  5997 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:47.743  5997  5997 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.743  5997  5997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:47.743  1017  1389 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5997 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:43:47.753  5997  5997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:47.753  1017  1389 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
06-22 07:43:47.753  5997  5997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.753  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.753  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.753  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.753  1017  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.763  6007  6007 E Zygote  : MountEmulatedStorage()
06-22 07:43:47.763  6007  6007 E Zygote  : v2
06-22 07:43:47.763  6007  6007 I libpersona: KNOX_SDCARD checking this for 10055
06-22 07:43:47.763  6007  6007 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.763  6007  6007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:47.773  6007  6007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:47.773  1017  1389 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6007 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
06-22 07:43:47.773  6007  6007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.783  5817  5817 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,06-22 07:43:47.783  1017  1485 I ActivityManager: Killing 5455:com.osp.app.signin/u0a36 (adj 15): empty #21,
06-22 07:43:47.783  1017  1473 I ActivityManager: Killing 5521:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,06-22 07:43:47.803  6007  6007 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.803  6007  6007 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.803  5997  5997 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.803  5997  5997 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.813  5964  5964 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-22 07:43:47.813  5964  5964 I PCWCLIENTTRACE_PushUtil: sales region : global
06-22 07:43:47.813  5964  5964 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-22 07:43:47.813  5964  5964 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,06-22 07:43:47.813  1017  3035 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,06-22 07:43:47.823  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.823  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.823  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.823  1017  3035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.823  5997  5997 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:43:47.843  6029  6029 E Zygote  : MountEmulatedStorage()
,06-22 07:43:47.843  6029  6029 E Zygote  : v2
06-22 07:43:47.843  6029  6029 I libpersona: KNOX_SDCARD checking this for 10029
06-22 07:43:47.843  5997  5997 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
06-22 07:43:47.843  6029  6029 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.853  1017  1390 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
06-22 07:43:47.853  1017  3035 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6029 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
06-22 07:43:47.853  1017  1390 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,06-22 07:43:47.853  6007  6007 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,06-22 07:43:47.853  1017  3035 I ActivityManager: Killing 5553:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,06-22 07:43:47.853  5978  5978 D ThemeInfoUtil: getCurrentFestivalName is [null]
06-22 07:43:47.853  5978  5978 D ThemeInfoUtil: isCurrentFestival = false
,06-22 07:43:47.863  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,06-22 07:43:47.863  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.863  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.863  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.863  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.873  6035  6035 E Zygote  : MountEmulatedStorage()
,06-22 07:43:47.873  6035  6035 E Zygote  : v2
06-22 07:43:47.873  6035  6035 I libpersona: KNOX_SDCARD checking this for 10148
06-22 07:43:47.873  6035  6035 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:47.883  1017  1136 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6035 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,06-22 07:43:47.883  6029  6029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:47.883  6035  6035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:47.883  6029  6029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:47.883  6029  6029 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.883  6007  6007 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,06-22 07:43:47.883  1017  1136 I ActivityManager: Killing 5539:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
06-22 07:43:47.883  6007  6007 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
06-22 07:43:47.883  6007  6007 D UserAnalysis: Create SecureDbHelper
,06-22 07:43:47.893  5706  5706 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,06-22 07:43:47.893  5706  5706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
06-22 07:43:47.893  1017  1136 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
06-22 07:43:47.893  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
06-22 07:43:47.893  6035  6035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:43:47.893  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:47.893  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:47.893  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,06-22 07:43:47.893  6035  6035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.903  5706  5706 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,06-22 07:43:47.903  6007  6007 D IntelligenceServiceApplication: onCreate()
,06-22 07:43:47.903  6007  6007 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,06-22 07:43:47.913  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,06-22 07:43:47.913  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.913  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.913  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.913  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.913  5706  6047 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,06-22 07:43:47.913  6035  6035 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.923  5706  6047 D FilterUnInstaller: before removeFromFS
,06-22 07:43:47.923  6007  6007 D IntelligenceServiceApplication: no applications having user consent for prediction
,06-22 07:43:47.923  6035  6035 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.933  6029  6029 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.933  6029  6029 D ActivityThread: Added TimaKeyStore provider,
,06-22 07:43:47.933  6060  6060 E Zygote  : MountEmulatedStorage(),
,06-22 07:43:47.933  6060  6060 E Zygote  : v2
06-22 07:43:47.933  6060  6060 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:47.933  6060  6060 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.933  6060  6060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:47.933  1017  1490 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,06-22 07:43:47.943  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,06-22 07:43:47.943  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.943  6060  6060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:47.943  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.943  6060  6060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:47.943  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.943  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.963  6075  6075 E Zygote  : MountEmulatedStorage()
06-22 07:43:47.963  6075  6075 E Zygote  : v2
06-22 07:43:47.963  6075  6075 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:47.963  6075  6075 I libpersona: KNOX_SDCARD not a persona
,06-22 07:43:47.963  6075  6075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:47.963  1017  1490 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6075 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:43:47.963  6075  6075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:47.963  1017  1490 I ActivityManager: Killing 5613:com.wsomacp/u0a23 (adj 15): empty #21
06-22 07:43:47.963  6075  6075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:47.963  6060  6060 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:47.963  6060  6060 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:47.983  1017  3953 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,06-22 07:43:47.983  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.983  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.983  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:47.983  1017  3953 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:43:47.993  6075  6075 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:43:47.993  6075  6075 D ActivityThread: Added TimaKeyStore provider
,06-22 07:43:48.003  6090  6090 E Zygote  : MountEmulatedStorage()
06-22 07:43:48.003  6090  6090 I libpersona: KNOX_SDCARD checking this for 10095
06-22 07:43:48.003  6090  6090 E Zygote  : v2
06-22 07:43:48.003  6090  6090 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:48.003  6090  6090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:43:48.003  1017  3953 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6090 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
06-22 07:43:48.003  6007  6007 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
06-22 07:43:48.003  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
06-22 07:43:48.003  6090  6090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:48.003  1017  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
06-22 07:43:48.003  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-22 07:43:48.003  6090  6090 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:43:48.003  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:48.003  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:48.003  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:43:48.023  6035  6035 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,06-22 07:43:48.033  6007  6007 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-22 07:43:48.033  6007  6007 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)

```
