# HAPP Routing Build Report

## Source
- Config: `/home/runner/work/ShadowRocket/ShadowRocket/shadowrocket.conf`
- Commit: `b44436c9dd4c10e4e19de7f4836555f0cdaa2795`

## Processed
- Rules in `[Rule]`: 14
- RULE-SET entries parsed: 1118
- Converted lines: 1107
- Dropped lines: 19

## Output
- Deeplink mode: `onadd`
- JSON length (compact): 779
- Deeplink length: 1061
- DirectSites: 2
- ProxySites: 1
- BlockSites: 0
- DirectIp: 3
- ProxyIp: 1
- BlockIp: 0

## DNS source
- Remote DNS source: `dns-server` -> `76.76.2.0`
- Domestic DNS source: `fallback-dns-server` -> `1.1.1.1`

## Dropped USER-AGENT
- google-all.list:946: USER-AGENT,%E4%BA%91%E7%AB%AF%E7%A1%AC%E7%9B%98*
- google-all.list:947: USER-AGENT,*YouTubeMusic*
- google-all.list:948: USER-AGENT,*com.google.Drive*
- google-all.list:949: USER-AGENT,*com.google.ios.youtubemusic*
- google-all.list:950: USER-AGENT,*youtube*
- google-all.list:951: USER-AGENT,Google.Drive*
- google-all.list:952: USER-AGENT,YouTube*
- google-all.list:953: USER-AGENT,YouTubeMusic*
- google-all.list:954: USER-AGENT,com.google.ios.youtube*
- google-all.list:955: USER-AGENT,com.google.ios.youtubemusic*

## Dropped DST-PORT
- none

## Dropped IP-ASN
- telegram.list:46: IP-ASN,211157,no-resolve
- telegram.list:47: IP-ASN,44907,no-resolve
- telegram.list:48: IP-ASN,59930,no-resolve
- telegram.list:49: IP-ASN,62014,no-resolve
- telegram.list:50: IP-ASN,62041,no-resolve

## Dropped composite AND
- shadowrocket.conf:44: AND,((PROTOCOL,UDP),(DEST-PORT,443)),REJECT-DROP
- shadowrocket.conf:45: AND,((PROTOCOL,UDP),(DEST-PORT,853)),REJECT-NO-DROP

## Other dropped reasons
- excluded_happ_ruleset: 2
