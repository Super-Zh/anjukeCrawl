# anjukeCrawl

安居客反爬虫机制做的较敏感，一定要写入头信息，避免被误认为黑客攻击。

url2local(url, header,cityzh) download the URL to local，以便出错后的排查

urlAnalysis(df,cityzh) 解析下载的网页

避免被反爬虫机制抓到，在每页下载完成后，让程序休息2s（time.sleep(2)）
