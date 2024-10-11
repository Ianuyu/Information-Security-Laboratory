資訊安全實驗報告
本報告展示了針對台北市政府全球資訊網進行的多層次資訊安全測試，涉及以下幾個階段：

資訊蒐集：使用公開資源和工具，如 Wayback Machine、SimilarWeb 和 Central Ops，取得網站的歷史紀錄、訪問者數據以及域名和 IP 位址等資訊。

服務掃描與漏洞檢測：使用 Nmap、Unicornscan 和 Amap 等工具掃描目標主機的開放端口及其運行的服務，接著使用 Nessus、Nikto 和 OWASP ZAP 進行漏洞檢測，找出安全漏洞並分析其嚴重程度。

網路攻擊：透過偽裝 Gateway 主機的 MAC 地址進行中間人攻擊，成功攔截目標主機的網路封包。
