## tcptools

### Pinging Popular Websites:

| Website     |        min       | avg | max | stddev |
| ----------- | ---------------- | --- | --- | ------ |
|    Amazon   | 18ms, 11ms, 17ms | 32ms, 15ms, 19ms | 53ms, 21ms, 21ms | 6.97ms |
|    Google   | 16ms, 16ms, 14ms | 63ms, 19ms, 19ms | 189ms, 23ms, 27ms | 22.75ms |
|  Microsoft  | 16ms, 17ms, 13ms | 25ms, 22ms, 19ms | 46ms, 27ms, 31ms  | 11.82ms |

### Was there any packet loss on any of the pings?
Overall, there was 0% reported packet loss on 9 of 9 pings.

### Did the IP address change for a given website between pings?
The IP address did not change for the same website between pings, but each website did have a different IP address. After waiting a while and coming back to www.google.com though, the IP address did slightly change, particularly the last two octets.

### Tracing Routes
#### What was the target server's IP address? How many hops were needed to reach the target? Identify the "class" of IP address for each major step in the trip

| Website     |  target server IP | total hops | class change |
| ----------- | ----------------- | ---------- | ------------ |
| Amazon | 18.65.223.187 | 10 | C, A |
| Google | 142.251.33.100 | 11 | C, A, B |
| Microsoft | 23.45.229.117 | 9 | C, A |

#### Can you identify your ISP from the intermediate server DNS names?
You can identify the Internet Service Provider from the intermediate server DNS names. For example, I noticed the phrase "seattle.wa.ibone.comcast.net" several times when pinging various websites. This is because comcast provides my internet services for my household (and street for that matter).
