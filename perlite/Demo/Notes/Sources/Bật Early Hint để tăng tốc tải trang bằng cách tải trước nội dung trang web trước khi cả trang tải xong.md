---
dg-publish: true
---
up:: [[../../Maps/Firefox MOC]]
tags:: #on/firefox 

# Bật Early Hint để tăng tốc tải trang bằng cách tải trước nội dung trang web trước khi cả trang tải xong

```javaScript
user_pref("network.early-hints.enabled", true);  
user_pref("network.early-hints.preconnect.enabled", true); 
user_pref ("network. Early-hints. Preconnect. Max_connections", 20); 
```