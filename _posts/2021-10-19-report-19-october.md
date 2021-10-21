---
layout: post
title: "Daily - October 19"
---

# AsyncStorage

Saya menggunakan library AsyncStorage ini untuk membuat session login. Library ini dapat diinstal dengan menggunakan perintah:

`npm install @react-native-async-storage/async-storage`

### AsyncStorage Login

`AsyncStorage.setItem('session_id', response.data.token)`

### AsyncStorage Check Login

`const isLogin = await AsyncStorage.getItem('session_id')`

### AsyncStorage Logout

`AsyncStorage.clear()`
