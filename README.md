# VR Bike Multiplayer - International College KMITL

| Contributive project to | IC Open House | 23 - 25 August 2018 |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1400" src="/photos/bike-01.jpg"> | <img width="1400" src="/photos/bike-02.jpg">|<img width="1400" src="/photos/bike-03.jpg">|
|<img width="1400" src="/photos/bike-04.jpg"> | <img width="1400" src="/photos/bike-07.gif"> | <img width="1400" src="/photos/bike-06.jpg"> |
|<img width="1400" src="/photos/bike-08.jpg"> | <img width="1400" src="/photos/bike-05.gif"> | <img width="1400" src="/photos/bike-09.jpg">|
| | | |
###### latest update : 29 Aug 2018

## Setting up
1. Attach magnets and sensors(a3144eua) on bikes
2. Wire the sensors into GPIO pins using pin 3/5, which are i2c, as input pins (you will need 2 rPi for 3 players)
3. Identically configure IP/Port in - sensor script`config.py` - server`config.py` - game client`4 times back menu` - monitor`4 times back menu` ( the IP that you can use is the accessible IP to the machine which runs server. I suggest you should use static IP )
4. Connect every piece of the system into the network
5. Run the server first
6. After that, run sensor script, game client and inspector client in any order (enter inspection mode by press M)
7. Start/Reset game from inspector client by pressing 'S' and 'R', respectively.

## Associated Repositories
- [Game/Inspector Client](https://github.com/maxoja/kmitl-vr-bike-unity)
- [Realtime Server](https://github.com/Nutthapat1234/bike-server)
- [Sensor Script - not ready yet]()

## Credits
##### Speed Sensor - `Bright` `Sun`
##### Realtime Socket Server - `Nut` [`Tawan`](https://github.com/maxoja)
##### VR Game/Inspector Client - [`Tawan`](https://github.com/maxoja) [`Dan AKA Tobalation`](https://github.com/Tobalation) `Tata` `Jui` `P'Ice`
##### Supporters & Sponsors - [`Samsung Thailand`](https://www.facebook.com/SamsungThailand/) [`T-Bike`](https://www.facebook.com/bikeisara/) [`International College & Staff`](https://www.facebook.com/interkmitl/) `P'Ham` `P'James` `Max` `Traphume` `Jia` `Tangthai` `Tonfah`
