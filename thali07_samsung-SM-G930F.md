#### Test 9856377440205b4_thali07_samsung-SM-G930F Logs


```
--------- beginning of system
12-19 14:46:06.973  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
12-19 14:46:07.653  8780  8780 I FIPS_bssl: FIPS approved mode (1) | 8780 | app_process
12-19 14:46:07.653  8780  8780 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-19 14:46:07.653  8780  8780 D AndroidRuntime: CheckJNI is OFF
12-19 14:46:07.653  8780  8780 D AndroidRuntime: readGMSProperty: start
12-19 14:46:07.653  8780  8780 D AndroidRuntime: readGMSProperty: already setted!!
12-19 14:46:07.653  8780  8780 D AndroidRuntime: propertySet: couldn't set property (it is from app)
12-19 14:46:07.653  8780  8780 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
12-19 14:46:07.653  8780  8780 D AndroidRuntime: readGMSProperty: end
12-19 14:46:07.653  8780  8780 D AndroidRuntime: addProductProperty: start
12-19 14:46:07.673  8780  8780 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-19 14:46:07.693  8780  8780 I Radio-JNI: register_android_hardware_Radio DONE
12-19 14:46:07.703  8780  8780 E AffinityControl: AffinityControl: registerfunction enter
12-19 14:46:07.703  8780  8780 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-19 14:46:07.763  8780  8780 D AndroidRuntime: Shutting down VM
,12-19 14:46:10.433  3497  4317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:46:10.433  3497  4317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:46:10.433  3497  4317 D BatteryService: online:4, current avg:166, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:165
12-19 14:46:10.433  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:46:10.443  3497  3497 I MotionRecognitionService: Plugged
,12-19 14:46:10.443  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:46:10.443  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:46:10.443  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:46:10.443  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:46:10.443  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:46:10.453  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 14:46:10.453  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:46:10.463  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:46:10.473  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:46:10.473  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:46:10.473  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:46:10.483  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 14:46:10.483  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:12.053  3497  6058 D SSRM:n  : SIOP:: AP = 320, PST = 370 (W:10), CP = 273, CUR = 166, LCD = 40
,12-19 14:46:20.493  3497  3517 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:46:20.493  3497  3517 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:46:20.493  3497  3517 D BatteryService: online:4, current avg:160, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:136
12-19 14:46:20.493  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:46:20.493  3497  3497 I MotionRecognitionService: Plugged
12-19 14:46:20.493  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:46:20.493  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:46:20.493  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:46:20.503  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:46:20.503  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 14:46:20.503  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 14:46:20.503  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:46:20.513  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:46:20.523  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:46:20.523  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:46:20.523  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:46:20.533  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:20.533  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:22.073  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 353 (W:10), CP = 271, CUR = 160, LCD = 40
,12-19 14:46:26.963  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:46:30.543  3497  4060 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:46:30.543  3497  4060 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:46:30.543  3497  4060 D BatteryService: online:4, current avg:152, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:145
12-19 14:46:30.543  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:46:30.553  3497  3497 I MotionRecognitionService: Plugged
12-19 14:46:30.553  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:46:30.553  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:46:30.553  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:46:30.553  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:46:30.553  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:46:30.563  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 14:46:30.563  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:46:30.573  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:46:30.573  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 14:46:30.573  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:46:30.583  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:46:30.593  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:30.593  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:31.143  3497  4139 E Watchdog: !@Sync 4 [12-19 14:46:31.153]
,12-19 14:46:32.103  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 335 (W:10), CP = 270, CUR = 152, LCD = 40
,12-19 14:46:32.373  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 14:46:32.373  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 14:46:39.793  4230  5794 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,12-19 14:46:40.603  3497  3979 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:46:40.603  3497  3979 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:46:40.603  3497  3979 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:143
12-19 14:46:40.603  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:46:40.603  3497  3497 I MotionRecognitionService: Plugged
12-19 14:46:40.603  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:46:40.603  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:46:40.603  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:46:40.613  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:46:40.613  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:46:40.613  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:46:40.613  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:46:40.623  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:40.623  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:46:40.633  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 14:46:40.633  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:46:40.633  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:46:40.653  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:42.123  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 324 (W:10), CP = 269, CUR = 145, LCD = 40
,12-19 14:46:46.973  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:46:50.653  3497  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:46:50.663  3497  3973 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:46:50.663  3497  3973 D BatteryService: online:4, current avg:140, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:135
12-19 14:46:50.663  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:46:50.663  3497  3497 I MotionRecognitionService: Plugged
12-19 14:46:50.663  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:46:50.663  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:46:50.663  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:46:50.673  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:46:50.673  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:46:50.673  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:46:50.673  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:46:50.683  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:46:50.693  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:46:50.693  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:46:50.693  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:46:50.703  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:50.703  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:46:52.153  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 319 (W:10), CP = 268, CUR = 140, LCD = 40
,12-19 14:46:52.863  3497  3808 V AlarmManager: Expired Alarm result :4
,12-19 14:46:52.883  3497  3586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b03dd2 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d0e55e 4230:com.google.android.gms.persistent/u0a19}
,12-19 14:46:52.903  3497  3516 V AlarmManager:  remove PendingIntent] PendingIntent{44c7ea3: PendingIntentRecord{5a60257 com.google.android.gms broadcastIntent}}
,12-19 14:46:52.993  4559  8805 D UdcContextInitService: registered all accounts: true
,12-19 14:46:53.083  3497  4395 V AlarmManager:  remove PendingIntent] PendingIntent{4901559: PendingIntentRecord{5a60257 com.google.android.gms broadcastIntent}}
,12-19 14:46:53.413  4230  8807 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-19 14:46:53.423  4230  8807 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-19 14:46:53.733  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:53.733  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 14:46:53.733  3150  3711 D EnterpriseController: netId is 0
12-19 14:46:53.733  3150  3711 D Netd    : getNetworkForDns: using netid 502 for uid 10019
,12-19 14:46:53.783  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:53.823  4230  8807 I qtaguid : Tagging socket 67 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:54.133  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.133  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.143  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:54.433  4230  8807 W Uploader: GMM_PRIMES no longer exists, so no auth token.
,12-19 14:46:54.443  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.443  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.443  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:54.493  4230  4238 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@90ea186)
,12-19 14:46:54.553  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.553  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.553  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:54.663  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.663  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.663  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:54.783  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.783  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.783  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:54.903  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.903  4230  8807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:46:54.903  4230  8807 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4230, getuid(): 10019
,12-19 14:46:55.053  3497  4395 V AlarmManager:  remove PendingIntent] PendingIntent{5fc8acd: PendingIntentRecord{5a60257 com.google.android.gms broadcastIntent}}
,12-19 14:46:59.993  3497  3808 V AlarmManager: Expired Alarm result :8
,12-19 14:46:59.993  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 14:46:59.993  3930  3930 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 14:47:00.013  3930  3930 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 14:47:00.073  3930  3930 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 14:47:00.093  4682  4682 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 14:47:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 14:47:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 14:47:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 14:47:00.103  4682  4682 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 14:47:00.103  4682  4682 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 14:47:01.143  3497  4139 E Watchdog: !@Sync 5 [12-19 14:47:01.155]
,12-19 14:47:02.213  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 316 (W:14), CP = 268, CUR = 140, LCD = 40
,12-19 14:47:06.973  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:47:12.243  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 312 (W:14), CP = 267, CUR = 140, LCD = 40
,12-19 14:47:20.703  3497  4804 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:47:20.703  3497  4804 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:47:20.703  3497  4804 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 14:47:20.703  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:47:20.713  3497  3497 I MotionRecognitionService: Plugged
,12-19 14:47:20.713  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:47:20.713  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:47:20.713  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:47:20.713  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:47:20.723  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:47:20.723  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:47:20.723  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:47:20.733  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:47:20.743  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:47:20.743  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:47:20.743  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:47:20.763  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 14:47:20.763  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:47:22.263  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 312 (W:14), CP = 267, CUR = 9, LCD = 40
,12-19 14:47:26.973  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:47:31.153  3497  4139 E Watchdog: !@Sync 6 [12-19 14:47:31.156]
,12-19 14:47:32.323  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 266, CUR = 9, LCD = 40
,12-19 14:47:32.413  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 14:47:32.413  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 14:47:32.503  4359  4422 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 87ms lastUpdatedAfter : 130657ms
,12-19 14:47:42.343  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 309 (W:14), CP = 266, CUR = 9, LCD = 40
,12-19 14:47:46.973  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:47:50.753  3497  3516 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:47:50.753  3497  3516 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:47:50.753  3497  3516 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 14:47:50.753  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:47:50.763  3497  3497 I MotionRecognitionService: Plugged
12-19 14:47:50.763  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:47:50.763  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:47:50.763  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:47:50.763  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:47:50.763  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:47:50.763  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:47:50.763  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:47:50.783  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:47:50.783  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:47:50.783  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:47:50.783  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:47:50.793  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 14:47:50.793  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:47:52.373  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 265, LCD = 40
,12-19 14:47:59.993  3497  3808 V AlarmManager: Expired Alarm result :8
,12-19 14:47:59.993  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-19 14:47:59.993  3930  3930 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 14:48:00.013  3930  3930 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 14:48:00.073  3930  3930 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 14:48:00.083  4682  4682 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 14:48:00.083  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 14:48:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 14:48:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 14:48:00.093  4682  4682 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 14:48:00.093  4682  4682 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 14:48:01.153  3497  4139 E Watchdog: !@Sync 7 [12-19 14:48:01.157]
,12-19 14:48:02.393  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 265, LCD = 40
,12-19 14:48:06.973  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:48:12.413  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 306 (W:14), CP = 265, LCD = 40
,12-19 14:48:20.803  3497  3517 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 14:48:22.473  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 264, LCD = 40
,12-19 14:48:26.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:48:31.153  3497  4139 E Watchdog: !@Sync 8 [12-19 14:48:31.159]
,12-19 14:48:32.533  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 264, LCD = 40
,12-19 14:48:32.603  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 14:48:32.603  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 14:48:42.553  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 304 (W:14), CP = 264, LCD = 40
,12-19 14:48:46.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:48:50.853  3497  4401 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:48:50.853  3497  4401 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:48:50.853  3497  4401 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 14:48:50.853  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:48:50.853  3497  3497 I MotionRecognitionService: Plugged
,12-19 14:48:50.853  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:48:50.853  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:48:50.853  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:48:50.863  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:48:50.863  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:48:50.863  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:48:50.863  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:48:50.873  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:48:50.883  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:48:50.883  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:48:50.883  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:48:50.903  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:48:50.903  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:48:52.583  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 303 (W:14), CP = 264, LCD = 40
,12-19 14:48:59.993  3497  3808 V AlarmManager: Expired Alarm result :8
,12-19 14:48:59.993  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 14:48:59.993  3930  3930 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 14:49:00.013  3930  3930 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 14:49:00.083  3930  3930 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 14:49:00.093  4682  4682 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 14:49:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 14:49:00.103  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 14:49:00.103  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 14:49:00.103  4682  4682 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
12-19 14:49:00.103  4682  4682 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 14:49:01.153  3497  4139 E Watchdog: !@Sync 9 [12-19 14:49:01.163]
,12-19 14:49:02.643  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 264, LCD = 40
,12-19 14:49:06.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:49:12.673  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 264, LCD = 40
,12-19 14:49:12.773  3497  3508 I art     : Background sticky concurrent mark sweep GC freed 146603(9MB) AllocSpace objects, 165(3MB) LOS objects, 26% free, 37MB/50MB, paused 3.263ms total 116.954ms
,12-19 14:49:20.893  3497  4409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 14:49:22.723  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:14), CP = 264, LCD = 40
,12-19 14:49:26.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:49:28.633  3497  3799 D TimaService: TIMA: TimaService scheduler is intialized. 
12-19 14:49:28.633  3497  3799 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
12-19 14:49:28.633  3497  3798 D TimaService: TimaServiceHandler.handleMessage what =1
,12-19 14:49:28.633  3497  3799 I TLC_TIMA_PKM_initialize: initializing...
12-19 14:49:28.633  3497  3799 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
12-19 14:49:28.633  3497  3799 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: device_id = 0x0
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: tlc_open() was called
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: Opening MobiCore device
12-19 14:49:28.633  3497  3799 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-19 14:49:28.633  3497  3799 I TZ: mc_tlc_communication: Opening the session
,12-19 14:49:28.683  3497  3799 I TZ: mc_tlc_communication: tlc_open() succeeded
12-19 14:49:28.683  3497  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,12-19 14:49:28.693  3497  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,12-19 14:49:28.723  3497  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,12-19 14:49:28.733  3497  3799 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,12-19 14:49:28.733  3497  3799 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,12-19 14:49:31.153  3497  4139 E Watchdog: !@Sync 10 [12-19 14:49:31.164]
,12-19 14:49:32.033  3497  3799 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
12-19 14:49:32.033  3497  3799 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,12-19 14:49:32.043  3497  3799 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-19 14:49:32.043  3497  3799 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-19 14:49:32.123  3497  3808 V AlarmManager: Expired Alarm result :4
,12-19 14:49:32.143  3497  3586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{881bcda u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7683a4 4559:com.google.android.gms/u0a19}
,12-19 14:49:32.163  8827  8827 E Zygote  : v2
12-19 14:49:32.173  8827  8827 I libpersona: KNOX_SDCARD checking this for 1000
12-19 14:49:32.173  8827  8827 I libpersona: KNOX_SDCARD not a persona
12-19 14:49:32.173  3497  3808 I ActivityManager: Start proc 8827:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,12-19 14:49:32.173  8827  8827 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,12-19 14:49:32.173  8827  8827 E Zygote  : accessInfo : 0
,12-19 14:49:32.183  4115  4115 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,12-19 14:49:32.183  4115  4115 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-19 14:49:32.193  4115  4115 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,12-19 14:49:32.213  8827  8827 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 14:49:32.213  8827  8827 D ActivityThread: Added TimaKeyStore provider
,12-19 14:49:32.243  8827  8827 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,12-19 14:49:32.243  3497  4161 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 14:49:32.243  8827  8827 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 14:49:32.243  8827  8827 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 14:49:32.243  4559  8839 I EventLogService: Aggregate from 1482153420149 (log), 1482153420149 (data)
,12-19 14:49:32.253  8827  8827 I InjectionManager: Inside getClassLibPath caller 
,12-19 14:49:32.253  8827  8827 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,12-19 14:49:32.253  8827  8827 D InjectionManager: InjectionManager
12-19 14:49:32.253  8827  8827 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,12-19 14:49:32.253  8827  8827 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
12-19 14:49:32.253  8827  8827 I InjectionManager: featureStore :{}
,12-19 14:49:32.293  3497  4804 I ActivityManager: Killing 8336:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): DHA:empty #33
,12-19 14:49:32.323  3497  4401 D ActivityManager: cleanUpApplicationRecord -- 8336
,12-19 14:49:32.323  3497  4401 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,12-19 14:49:32.373  3497  3586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{92c13d u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a98a7eb 7956:com.samsung.android.sm/1000}
,12-19 14:49:32.383  3497  4315 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{78b0d32 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a98a7eb 7956:com.samsung.android.sm/1000}
,12-19 14:49:32.703  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 14:49:32.703  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 14:49:32.763  3497  6058 D SSRM:n  : SIOP:: AP = 310, PST = 301 (W:10), CP = 264, LCD = 40
,12-19 14:49:36.173  3150  3708 D Netd    : Iface wlan0 link up
,12-19 14:49:36.173  4115  4115 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
12-19 14:49:36.173  5010  5238 D PdnController: Interface Changed wlan0 link up
12-19 14:49:36.173  3497  3590 D Tethering: interfaceLinkStateChanged wlan0, true
12-19 14:49:36.173  3497  3590 D Tethering: interfaceStatusChanged wlan0, true
,12-19 14:49:36.173  4115  4115 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,12-19 14:49:36.183  3497  3851 D WifiP2pService: InactiveState{ what=147461 }
,12-19 14:49:36.183  3497  3851 D WifiP2pService: P2pEnabledState{ what=147461 }
,12-19 14:49:36.183  3497  3851 D WifiP2pService: DefaultState{ what=147461 }
,12-19 14:49:36.223  3497  3497 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-19 14:49:36.233  3497  3586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae60a83 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7948ee6 3930:com.android.systemui/u0a62}
,12-19 14:49:42.793  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:10), CP = 264, LCD = 40
,12-19 14:49:46.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:49:50.943  3497  3847 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 14:49:52.833  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:10), CP = 264, LCD = 40
,12-19 14:49:56.703  8579  8622 W PlayEventLogger: No account for auth token provided
,12-19 14:49:56.713  8579  8622 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 14:49:56.713  8579  8622 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 14:49:56.713  3150  3711 D EnterpriseController: netId is 0
,12-19 14:49:56.713  3150  3711 D Netd    : getNetworkForDns: using netid 502 for uid 10032
,12-19 14:49:59.993  3497  3808 V AlarmManager: Expired Alarm result :8
,12-19 14:49:59.993  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 14:49:59.993  3930  3930 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 14:50:00.013  3930  3930 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 14:50:00.073  3930  3930 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 14:50:00.083  4682  4682 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 14:50:00.083  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 14:50:00.083  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 14:50:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 14:50:00.093  4682  4682 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 14:50:00.093  4682  4682 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 14:50:01.153  3497  4139 E Watchdog: !@Sync 11 [12-19 14:50:01.166]
,12-19 14:50:02.883  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:10), CP = 264, LCD = 40
,12-19 14:50:06.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:50:12.913  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:14), CP = 263, LCD = 40
,12-19 14:50:20.993  3497  4401 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:50:20.993  3497  4401 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:50:20.993  3497  4401 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 14:50:20.993  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:50:21.003  3497  3497 I MotionRecognitionService: Plugged
12-19 14:50:21.003  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:50:21.003  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:50:21.003  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:50:21.003  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:50:21.003  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:50:21.003  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:50:21.003  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:50:21.023  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:50:21.033  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 14:50:21.033  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:50:21.033  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:50:21.053  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 14:50:21.053  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:50:22.933  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:50:26.983  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:50:31.163  3497  4139 E Watchdog: !@Sync 12 [12-19 14:50:31.167]
,12-19 14:50:32.723  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 14:50:32.723  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 14:50:32.803  4359  4422 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 78ms lastUpdatedAfter : 180303ms
,12-19 14:50:32.993  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:50:43.013  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:50:46.993  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:50:51.043  3497  4463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 14:50:51.043  3497  4463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 14:50:51.043  3497  4463 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 14:50:51.043  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 14:50:51.053  3497  3497 I MotionRecognitionService: Plugged
12-19 14:50:51.053  3497  3497 D MotionRecognitionService:   cableConnection= 1
12-19 14:50:51.053  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 14:50:51.053  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,12-19 14:50:51.053  3497  3855 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 14:50:51.053  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 14:50:51.063  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 14:50:51.063  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 14:50:51.073  5010  5010 D CommonServiceConfiguration: getStringValueSetting
,12-19 14:50:51.073  4962  4962 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 14:50:51.073  4962  5346 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 14:50:51.083  5010  5010 D BatteryMonitor: new battery level: 100
,12-19 14:50:51.103  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:50:51.103  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 14:50:53.043  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:50:59.993  3497  3808 V AlarmManager: Expired Alarm result :8
,12-19 14:50:59.993  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 14:50:59.993  3930  3930 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 14:51:00.013  3930  3930 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 14:51:00.073  3930  3930 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 14:51:00.093  4682  4682 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 14:51:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 14:51:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 14:51:00.093  4682  4682 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 14:51:00.093  4682  4682 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 14:51:00.093  4682  4682 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 14:51:01.163  3497  4139 E Watchdog: !@Sync 13 [12-19 14:51:01.168]
,12-19 14:51:03.093  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:51:06.993  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:51:13.123  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:51:21.093  3497  4317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 14:51:23.183  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40
,12-19 14:51:26.993  3497  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 14:51:31.163  3497  4139 E Watchdog: !@Sync 14 [12-19 14:51:31.170]
,12-19 14:51:32.883  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 14:51:32.883  4359  4422 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 14:51:33.243  3497  6058 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 263, LCD = 40

```
