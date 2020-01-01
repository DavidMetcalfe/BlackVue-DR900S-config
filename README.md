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
