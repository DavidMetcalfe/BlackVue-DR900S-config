# BlackVue-DR900S-config
The below table contains the config.ini settings of the BlackVue DR900S dashcam and their meaning. These details are obtained via BlackVue support and through my own experimentation and are thus not fully complete. If you find areas of improvement, please open an issue or submit a pull request with updated information.

| [Tab1] | Description |
| --- | --- |
| TimeSet=0	| 1 = Manual time Setting, 0 = Sync with GPS time |
| SetTime=0100	| Manually set time. Always in 24-hour format. Example = 1 a.m. |
| TimeZone=-1100	| System timezone in Greenwich Mean Time (GMT). Example = GMT-11 |
| Daylight=0 | Daylight savings time. 0 = No, 1 = Yes |
| GpsSync=1	| Sync with GPS. 1 = Yes 0 = No |
| ImageSetting=0 | Resolution: 0 = 4K UHD 30FPS (Extreme), 1 = 4K UHD 30FPS, 2 = FHD 60FPS, 3 = FHD 30FPS |
| VideoQuality=0 | Image quality: 0 = Highest, 1 = High, 2 = Normal |
| NightVision=0	| HDR Night Vision: 0 = Off, 1 = On (Always), 2 = On (Parking Mode only) |
| FrontBrightness=2	| Brightness of Front camera |
| RearBrightness=2 | Brightness of Rear camera (for 2CH setups) | 
| RearParkingMode=0 |	Rear Camera recording in parking mode : 0 = Off, 1 = On |
| NormalRecord=1 | Normal recording: 1 = On, 0 = Off |
| VoiceRecord=1	| Voice recording : 1 = On, 0 = Off |
| DateDisplay=1	| Date & Time Display: 1 = On, 0 = Off |
| SpeedUnit=0 |	Speed Unit: 0 = km/h, 1 = MPH, 2 = Off |
| RecordTime=2 | Video Segment Length: 1 = 1 min, 2 = 2 min, 3 = 3 min |
| LockEvent=0	| Lock Event Files: 1= On; 0 = Off |
| OverwriteLock=1 |	Overwrite Lock Files: 1= On; 1 = Off |
| RearRotate=0 | Rear Camera Orientation: 0 = Default, 1 = Rotate Video 180', 2 = Mirror Video |
| VCodecType=1 | Video Codec: 0 = H.265, 1 = H.264 |
| HDR=0	| HDR Night Vision: 0 = Off, 1 = On (Always), 2 = On (Parking Mode only) |
| FrontRotate=0	| Front camera rotation: 0 = Off, 1= On |

| [Tab1] | Description |
| --- | --- |
| NORMALSENSOR1=0 |	G-Sensor (Normal mode) Up, Down |
| NORMALSENSOR2=0 |	G-Sensor (Normal mode) Side to Side |
| NORMALSENSOR3=0 |	G-Sensor (Normal mode)Front and Back |
| PARKINGSENSOR1=8 | G-Sensor (Parking Mode) Up, Down |
| PARKINGSENSOR2=8 | G-Sensor (Parking mode) Side to Side |
| PARKINGSENSOR3=8 | G-Sensor (Parking mode)Front and Back |
| MOTIONSENSOR=5 | Motion detection (Parking mode) |
| FrontMotionRegion=65535 |	Front camera motion detection region |
| RearMotionRegion=65535 | Rear camera motion detection region |

| [Tab3] | Description |
| --- | --- |
| RECLED=1 | LED Recording status: 1 = On, 0 = Off |
| NORMALLED=1 |	Front Security (Normal Mode): 1 = On, 0 = Off |
| PARKINGLED=0 | Front Security (Parking Mode): 1 = On, 0 = Off |
| RearLED=0 |	Rear Security: 1 = On, 0 = Off (for 2CH setups) |
| WifiLED=0	| Wi-Fi (Parking Mode): 1 = On, 0 = Off |
| PSENSOR=0	| Proximity Sensor: 0 = Voice recording On/Off, 1 = Manual recording, 2 = Off |
| STARTVOICE=1 | Voice Guidance, Power On: Checked = On, Unchecked = Off |
| NORMALSTARTVOICE=1 | Starting Normal Recording: Checked = On, Unchecked = Off |
| EVENTSTARTVOICE=0	| Starting Event Recording: Checked = On, Unchecked = Off |
| CHANGERECORDMODEVOICE=0	| Changing Recording Mode: Checked = On, Unchecked = Off |
| ENDVOICE=1 | Power Off: Checked = On, Unchecked = Off |
| SPEEDALERTVOICE=0	| Speed Alert: Checked = On, Unchecked = Off |
| CLOUDVOICE=0 | Cloud Related: Checked = On, Unchecked = Off |
| PARKINGEVENTVOICE=0	| Impact Dertected in Parking mode: Checked = On, Unchecked = Off |
| VOLUME=5 | Volume |
| ScheduledReboot=1	| Scheduled Reboot: 1 = On, 0 = Off |
| ScheduledRebootTime=3 |	Set time |
| SpeedAlert=2 | Speed Alert: 0 = km/h, 1 = Mph, 2 = Off |
| kmLimit=0	| Km/h value |
| mileLimit=0 |	Mph value |
| userString=Example	| User text overlay ("Example") |

| [Wifi] | Description |
| --- | --- |
|ap_ssid=Blackvue900S-C12C69 | Login credentials, Wi-Fi SSID
| ap_pw=5181178AEB83EDE2230DA62AF55B537EFA6F18A66443E4A545A2DCB5AFB4756D	| Encrypted and hashed password |
| onstart=1	| Wifi Autoturn on: 1 = On, 0 = Off |
| WifiSleepMode=0 |	Wifi Autoturn off: 1= On, 0 = Off |
| WiFiBand=1 | Wi-Fi Band: 0 = 5 Ghz, 1 = 2.4 Ghz |

| [Cloud] | Description |
| --- | --- |
| CloudService=1 | Enable cloud service: 1 = On, 0 = Off |
| sta_ssid=COI_Admin | Cloud service hotspot settings 1 SSID |
| sta_pw=594EB00E64E821A6C9C01CAFD2C16ED7C0F5C781C59E57C250C76AF47BC8ED25	| Encrypted and hashed password |
| sta_garage=0 | Garage setting: 0 = not set, 1 = set |
| sta2_ssid=CO_Managers	| Cloud service hotspot settings 2 SSID |
| sta2_pw=1DC573DB7A6C0B50F9F7CEBB6FC9812B4BF59BA0FA9042C8081119AB09CA0274 | Encrypted and hashed password |
| sta2_garage=1	| Garage setting: 0 = not set, 1 = set |
| sta3_ssid=Example	| Cloud service hotspot settings 3 SSID |
| sta3_pw=1CC573DB7A6C0B50F9F7CEBB6FC9812B4BF59BA0FA9042C8081119AB09CA0275 | Encrypted and hashed password |
| sta3_garage=0 |	Garage setting: 0 = not set, 1 = set |
| AlarmManual=1	| Push Notification Manual recording :1 = On, 0 = Off |
| AlarmParking=0 | Motion detection (Parking mode): 1 = On, 0 = Off |
| AlarmParkEvent=0 | Event detection (Parking mode): 1 = On, 0 = Off |
| AlarmEvent=1 | Event detection (Norml mode): 1 = On, 0 = Off |
| AlarmSpeed=1 | Overspeed (Normal mode): 1 = On, 0 = Off |
| AlarmParkInOut=1 | Enter/Exit Parking mode: 1 = On, 0 = Off |
| AlarmHighTemperature=1 | High Temperature warning: 1 = On, 0 = Off |
