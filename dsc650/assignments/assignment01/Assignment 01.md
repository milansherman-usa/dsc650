---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Milan Sherman
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     |
| 1024x768 PNG image                         | 1.7 MB        |
| 1024x768 RAW image                         | 2.25 MB       | 
| HD (1080p) HEVC Video (15 minutes)         | 900 MB        |
| HD (1080p) Uncompressed Video (15 minutes) | 56,953.125    |
| 4K UHD HEVC Video (15 minutes)             | 2,625 MB      |
| 4k UHD Uncompressed Video (15 minutes)     | 227,812.5 MB  |
| Human Genome (Uncompressed)                | 0.77 GB       |

128 characters @ 1 byte/character = 128 bytes
1024x768 = 78336 pixels x 24 bits/pixel = 2,359,296 bits x 1 byte/8 bits x 1 kilobyte/1024 bytes x 1 megabyte/1024 kilobytes = 2.25 MB
Assuming png compression of 25%, 2.25MB x .75 = 1.6875 MB
4k Video Raw (4096 x 2160 pixels): 
15 minutes x 60 seconds/minute x 30 frames per second x (4096 x 2160) pixels x 8 bits/pixel x 1 byte/8 bits x 1 kilobyte/1024 bytes x 1 megabyte/1024 kilobytes = 227,812.5 MB
1 minutes of 4k video at 30 fps = 175 MB for HEVC x 15 = 2625 MB
HD (1080p) has 25% of the pixels as 4K
HD (1080p) HEVC:  2625/4 = 656.25 MB
HD (1080p) Uncompressed: 227,812.5/4 = 56,953.125

#### b. Scaling

|                                           | Size     | # HD | 
|-------------------------------------------|---------:|-----:|
| Daily Twitter Tweets (Uncompressed)       | ??       |      |
| Daily Twitter Tweets (Snappy Compressed)  | ??       |      |
| Daily Instagram Photos                    | ??       |      |
| Daily YouTube Videos                      | ??       |      |
| Yearly Twitter Tweets (Uncompressed)      | ??       |      |
| Yearly Twitter Tweets (Snappy Compressed) | ??       |      |
| Yearly Instagram Photos                   | ??       |      |
| Yearly YouTube Videos                     | ??       |      |

59.4 millions tweets per day x 300 bytes 

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | ??   |            |
| Twitter Tweets (Snappy Compressed) | ??   |            |
| Instagram Photos                   | ??   |            |
| YouTube Videos                     | ??   |            |

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | ? ms                 |
| Low Earth Orbit Satellite | ? ms                 |
| Geostationary Satellite   | ? ms                 |
| Earth to the Moon         | ? ms                 |
| Earth to Mars             | ? minutes            | 
