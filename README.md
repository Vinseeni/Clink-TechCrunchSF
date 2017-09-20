# Some Simple set up instructions

Preview of NVC Ready Branch:

![](https://lh3.googleusercontent.com/jcoIyXV3cLyi9kf9JdCwmH1SDTI8QqBUwbk5ZjcAm2j6jf4WX5E49WD6rBUrnTyfaLqRFaMAH8iMRO4wKaQV_7NtAbvF2OpnlSPcjUg6EXSE13LU2YLSHtR-isHww0tS12ghiHbwOvcUlqnzpc-a49cctR5nR-kmCB8Dwgurm1mQKHQCxKAGh-jVeQ-ggvP5O4ufko9xYTblKgCzT1-8Q7zaA7-wsByLxsGw0D0U6X2bTBhxOyyp-07vfoK8hfhjAkaKO0UV0Xrc7aXBTafS8JWB0hbX8W0ILF-vVOa8_lh43lcfa1AWvD0M-Sp9QpzZqopVk0fb00Eof6iBL5SxbL89R0u7Nr3kGY-Xj7ys5Mzw2bb7uK-ykqO7tIFvlNk3hhHZd3fFdxZYeBdYhTHKpKW6hdzjWneNINVpXxcpLAFZkFw7nIB3IK7o_bb_LOxx3LSgRskdInjhoeS_FD8MbQxVJgvETplQodEvhsk3Qs6X3PB_aepfy4rb0qJPrxu1Rg7qZt727Qf8-uqWkXeRRKlbErxi3SI7663e8DGx_8RJ6oKp6yD3aCvX7c6jzDNyWuhUD0gIRVeW80BpQCiBmi8S8EdNEs6k4-QhY9lmVEFmoRbfI_zuWpFTLTQFGCQp17KNC0xvBRK_qcSwJh2y8An7cirskaCv_ad0=w345-h613-no)

https://goo.gl/photos/PfyZ11wTwcsVeqE26

Follow the instructions of react native set up from here 

https://facebook.github.io/react-native/releases/next/docs/getting-started.html

run `npm install` to save your ass
The two codes below in two separate terminals. Start with  `react-native start`
```
react-native start
react-native run-android
```

Use android studio to make sure you have `Build tools 23.0.1` and `android-23`, set up env var `$ANDROID_HOME=<where ever your sdk is>` in your respective windows/mac stuff

if you get some watchman errors:

```
npm r -g watchman
brew update && brew upgrade
brew install watchman
```
