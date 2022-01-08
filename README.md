Just (no) Desserts
===

This is a linter that enforces zero usages of Android's marketing names for their versions (desserts till recent years).

This is quite simply due to the fact the API documentation uses numbers, and the marketing terms are thrown in by the
IDE as it auto fixes warnings about SDK versions.

This also has a lint quick fix that puts the correct number in for you.

This came from the Signal Android source https://github.com/signalapp/Signal-Android