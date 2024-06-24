
## Send message
curl 'https://www.linkedin.com/voyager/api/voyagerMessagingDashMessengerMessages?action=createMessage' \

-H 'accept: application/json' \

-H 'accept-language: en-US,en;q=0.5' \

-H 'content-type: text/plain;charset=UTF-8' \

-H 'cookie: li_sugr=af9190ab-dba8-4f8d-9d1e-f28d7be9c6b3; bcookie="v=2&48335e1f-e1b4-4df3-8f55-2da9fcc41702"; UserMatchHistory=AQL4Pv8auSKOOQAAAY-i4nMq9LkUd6GQOUBU_NiH-m-Srx9mvHm_N6Ts_Pzec-luPnToWTJ4X3jEQg; AnalyticsSyncHistory=AQKFSriSZBN_ggAAAY-i4nMqxP52TVF-_keI8MIZCFn2024EOrHLvLUal1l5h57-BtJBPYBYK7Eft4WHvqQ94g; bscookie="v=1&202405230038209e9b8b17-e662-4c50-8ea2-59dcc46f3860AQFPikpqnz_H5RZrylNjlI_RUxJBAyLL"; li_rm=AQGMe-1h6VnRdQAAAY-7L4tmytYztBrwVUaIlCtd_P9z-DMHPUDJVeqhViXNC-FKu3Wd0aQo-QgGp9gqtosL4ZjtTqXsIm0nrAz_I5IqIAM5FM2odbBq1qPv; li_at=AQEDAR84AyIBPgC5AAABj7svlRkAAAGP3zwZGU0Af1gPbud9nxl-RRvx605goL7_SxGB91huBpI2YeP1_ceMPA5N8dlfpDXGQHe5zL4WGXziWRQAqmk-i_-2LLaFgznT_ae7GDZfkHMoYdZAwOaDCVnC; liap=true; JSESSIONID="ajax:6431800537235777633"; lang=v=2&lang=en-us; timezone=America/Sao_Paulo; li_theme=light; li_theme_set=app; dfpfpt=d0246ee833dd4d779329772ddfa373a6; fptctx2=taBcrIH61PuCVH7eNCyH0AHEYHVht29NHm46S5qgUjbPjT1Y7T0SlDMzkSd6Kp75yWwCiuIUeYyBAohPNQzOH8N5f%252bULPEr%252fm%252brdAExJg5XXzHiRP%252fFn7jImGDWvAOPY3shYLANT0wxOV%252bMJu8%252bC8zoWjad1BhiIOjuwBgfg0M6ORCRx8RBqL16gMGr3sA8xeH9p9sYNdcHLUsz51FTSgfoEd4lstz4FtpjZcHWJ9kEYD9r4Zecue2pWgH374ztgueH%252bL9Z28Gw7VHdekT%252ba5uLf%252b%252fKwLZAZ0vxwOQJVo%252bQgp%252fPtyLtE1DR%252bfLvGXFIZYnTYScSsq5XLQ1UiKBv4H2Vi97tB972zr%252bJ7sEoPNso%253d; lidc="b=VB14:s=V:r=V:a=V:p=V:g=5477:u=1095:x=1:i=1716833170:t=1716919570:v=2:sig=AQF8yV24L1DxMGb5HPH3Yj_YJhB_FfU_"; sdsc=1%3A1SZM1shxDNbLt36wZwCgPgvN58iw%3D' \

-H 'csrf-token: ajax:6431800537235777633' \

-H 'origin: https://www.linkedin.com' \

-H 'priority: u=1, i' \

-H 'referer: https://www.linkedin.com/messaging/thread/2-NzI1NzFkNDctYzkzZS00MDkxLTg0YTQtZGQ5OWM3MDdiNjZlXzAxMw==/' \

-H 'sec-ch-ua: "Chromium";v="124", "Brave";v="124", "Not-A.Brand";v="99"' \

-H 'sec-ch-ua-mobile: ?0' \

-H 'sec-ch-ua-platform: "macOS"' \

-H 'sec-fetch-dest: empty' \

-H 'sec-fetch-mode: cors' \

-H 'sec-fetch-site: same-origin' \

-H 'sec-gpc: 1' \

-H 'user-agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36' \

-H 'x-li-lang: en_US' \

-H 'x-li-page-instance: urn:li:page:d_flagship3_messaging_conversation_detail;hcF5zqQlROCXJmYR+F5+gg==' \

-H 'x-li-track: {"clientVersion":"1.13.17226","mpVersion":"1.13.17226","osName":"web","timezoneOffset":-3,"timezone":"America/Sao_Paulo","deviceFormFactor":"DESKTOP","mpName":"voyager-web","displayDensity":2,"displayWidth":2838,"displayHeight":1688}' \

-H 'x-restli-protocol-version: 2.0.0' \

--data-raw $'{"message":{"body":{"attributes":[],"text":"to testando aqui p ver como manda mensagem no linkedin. Vou ficar spamando mensagem sepa kkk"},"renderContentUnions":[],"conversationUrn":"urn:li:msg_conversation:(urn:li:fsd_profile:ACoAAB84AyIBxRJwzOfQOHmYPp4d1_r09hnz4zo,2-NzI1NzFkNDctYzkzZS00MDkxLTg0YTQtZGQ5OWM3MDdiNjZlXzAxMw==)","originToken":"e51c94bf-1e51-4240-9f62-a562e4aac9cb"},"mailboxUrn":"urn:li:fsd_profile:ACoAAB84AyIBxRJwzOfQOHmYPp4d1_r09hnz4zo","trackingId":"å\\u001c\u0094¿\\u001eQB@\u009fb¥bäªÉË","dedupeByClientGeneratedToken":false}'

## Get message

curl 'https://www.linkedin.com/voyager/api/voyagerMessagingGraphQL/graphql?queryId=messengerMessages.d1b494ac18c24c8be71ea07b5bd1f831&variables=(conversationUrn:urn%3Ali%3Amsg_conversation%3A%28urn%3Ali%3Afsd_profile%3AACoAAB84AyIBxRJwzOfQOHmYPp4d1_r09hnz4zo%2C2-ODM0ODBhNmMtODFhMy00N2M3LWI3YjItYjJkNDc3ZjM3NjRiXzAxMg%3D%3D%29)' \

-H 'accept: application/graphql' \

-H 'accept-language: en-US,en;q=0.5' \

-H 'cookie: li_sugr=af9190ab-dba8-4f8d-9d1e-f28d7be9c6b3; bcookie="v=2&48335e1f-e1b4-4df3-8f55-2da9fcc41702"; UserMatchHistory=AQL4Pv8auSKOOQAAAY-i4nMq9LkUd6GQOUBU_NiH-m-Srx9mvHm_N6Ts_Pzec-luPnToWTJ4X3jEQg; AnalyticsSyncHistory=AQKFSriSZBN_ggAAAY-i4nMqxP52TVF-_keI8MIZCFn2024EOrHLvLUal1l5h57-BtJBPYBYK7Eft4WHvqQ94g; bscookie="v=1&202405230038209e9b8b17-e662-4c50-8ea2-59dcc46f3860AQFPikpqnz_H5RZrylNjlI_RUxJBAyLL"; li_rm=AQGMe-1h6VnRdQAAAY-7L4tmytYztBrwVUaIlCtd_P9z-DMHPUDJVeqhViXNC-FKu3Wd0aQo-QgGp9gqtosL4ZjtTqXsIm0nrAz_I5IqIAM5FM2odbBq1qPv; li_at=AQEDAR84AyIBPgC5AAABj7svlRkAAAGP3zwZGU0Af1gPbud9nxl-RRvx605goL7_SxGB91huBpI2YeP1_ceMPA5N8dlfpDXGQHe5zL4WGXziWRQAqmk-i_-2LLaFgznT_ae7GDZfkHMoYdZAwOaDCVnC; liap=true; JSESSIONID="ajax:6431800537235777633"; lang=v=2&lang=en-us; timezone=America/Sao_Paulo; li_theme=light; li_theme_set=app; dfpfpt=d0246ee833dd4d779329772ddfa373a6; fptctx2=taBcrIH61PuCVH7eNCyH0AHEYHVht29NHm46S5qgUjbPjT1Y7T0SlDMzkSd6Kp75yWwCiuIUeYyBAohPNQzOH8N5f%252bULPEr%252fm%252brdAExJg5XXzHiRP%252fFn7jImGDWvAOPY3shYLANT0wxOV%252bMJu8%252bC8zoWjad1BhiIOjuwBgfg0M6ORCRx8RBqL16gMGr3sA8xeH9p9sYNdcHLUsz51FTSgfoEd4lstz4FtpjZcHWJ9kEYD9r4Zecue2pWgH374ztgueH%252bL9Z28Gw7VHdekT%252ba5uLf%252b%252fKwLZAZ0vxwOQJVo%252bQgp%252fPtyLtE1DR%252bfLvGXFIZYnTYScSsq5XLQ1UiKBv4H2Vi97tB972zr%252bJ7sEoPNso%253d; lidc="b=VB14:s=V:r=V:a=V:p=V:g=5477:u=1095:x=1:i=1716833170:t=1716919570:v=2:sig=AQF8yV24L1DxMGb5HPH3Yj_YJhB_FfU_"; sdsc=1%3A1SZM1shxDNbLt36wZwCgPgvN58iw%3D' \

-H 'csrf-token: ajax:6431800537235777633' \

-H 'priority: u=1, i' \

-H 'referer: https://www.linkedin.com/messaging/thread/2-ODM0ODBhNmMtODFhMy00N2M3LWI3YjItYjJkNDc3ZjM3NjRiXzAxMg==/' \

-H 'sec-ch-ua: "Chromium";v="124", "Brave";v="124", "Not-A.Brand";v="99"' \

-H 'sec-ch-ua-mobile: ?0' \

-H 'sec-ch-ua-platform: "macOS"' \

-H 'sec-fetch-dest: empty' \

-H 'sec-fetch-mode: cors' \

-H 'sec-fetch-site: same-origin' \

-H 'sec-gpc: 1' \

-H 'user-agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36' \

-H 'x-li-lang: en_US' \

-H 'x-li-page-instance: urn:li:page:d_flagship3_messaging_conversation_detail;2UALHsiHQOW2L+eDTy9FtQ==' \

-H 'x-li-track: {"clientVersion":"1.13.17226","mpVersion":"1.13.17226","osName":"web","timezoneOffset":-3,"timezone":"America/Sao_Paulo","deviceFormFactor":"DESKTOP","mpName":"voyager-web","displayDensity":2,"displayWidth":2838,"displayHeight":1688}' \

-H 'x-restli-protocol-version: 2.0.0'