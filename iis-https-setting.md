# https and IIS settings
## background
***
許多個人網站都會採用https，考量於經濟效益，大多部屬自行架設於伺服器，要設定https需要完成下列幾個步驟。
1. 購買或索取免費的網域名稱並設定dns指向伺服器ip
2. 為伺服器設定憑證
3. 部屬網站並調整網站網址導向至https機制  
  
以下將假設使用者已做好網域的設定，僅以iis作為伺服器並設定

## references
***
1. [使用 Let's Encrypt](https://blog.xuite.net/tolarku/blog/584693076-%E4%BD%BF%E7%94%A8+Let%27s+Encryption+SSL+%E7%82%BA+IIS+%E5%B0%8E%E5%85%A5+https+%EF%BC%8C%E4%B8%A6%E5%BC%B7%E5%88%B6%E8%BD%89+http+%E8%87%B3+https+-+Windows)
2. [IIS-多站台共用port](https://blog.darkthread.net/blog/websites-sharing-80-port/)
3. [在iis上架設多個Https網站](https://poychang.github.io/iis-multi-domain-ssl/)
4. [伺服器使用多個ssl 證書](https://www.390seo.com/jishu/server/2807.html)
5. [IIS SNI說明-1](https://docs.microsoft.com/en-us/iis/get-started/whats-new-in-iis-8/iis-80-server-name-indication-sni-ssl-scalability)
6. [IIS SNI說明-2](https://blogs.msdn.microsoft.com/kaushal/2012/09/04/server-name-indication-sni-with-iis-8-windows-server-2012/)
