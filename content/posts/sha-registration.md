+++
title = "Implementing Google Authentication in Flutter (Android): A Guide to SHA Registration for Release Apps"
date = "2023-11-25"

[taxonomies]
tags=["Flutter", "Android"]

[extra]
comment = false
+++

In my development environment, Google authentication was successful, but I encountered authentication failures when releasing the app through Google Play.

For Android apps released via Google Play, it's necessary to use the SHA-1 certificate fingerprint set in the **Google Play Console**, not the one obtained from Android Studio, and add it to the Firebase console. 

