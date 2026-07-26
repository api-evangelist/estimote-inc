---
title: "Query shortIdentifier for Estimote Location in ipad os 17.5 not return shortIdentifier"
url: "https://forums.estimote.com/t/query-shortidentifier-for-estimote-location-in-ipad-os-17-5-not-return-shortidentifier/26201#post_1"
date: "2025-04-15"
author: "@SensorTeam2016 Sensor Team"
feed_url: "https://forums.estimote.com/posts.rss"
---
Hi Estimote and Forum We are facing issue from estimote sensor on latest ipad os 17.5 We can call ESTTelemetryNotificationTemperature to get temperature. The function can get it easily but it does not return shortIdentifier value. It is only return like this below ength=20,bytes=0 // Allocate a new call back for the SDK self.temperatureNotification = [[ESTTelemetryNotificationTemperature alloc] initWithNotificationBlock:^(ESTTelemetryInfoTemperature *temperature) { NSLog(@"SensorsViewController:doSleepAndStart:Temp2: %f %@", [temperature.temperatureInCelsius floatValue], temperature.shortIdent
