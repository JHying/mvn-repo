## 說明

<a href="https://github.com/JHying/mvn-repo/blob/main/LICENSE">![License: MIT](https://img.shields.io/badge/License-MIT-orange)

**Last Updated: 2024.02.27**

**Framework: spring boot 3.2.3**

**Version: JAVA JDK 17**

***

## db-utils

> version 3.0

1. BaseDAO (**USE:** extend BaseDAO)
2. QueryUtil (使用 CriteriaBuilder 操作資料庫, **USE:** new QueryUtil)

***

## shared-utils

> version 3.0

1. 統一 Response 格式 (**USE:** extend BaseController)
2. Http 工具 (採用 HttpURLConnection, **USE:** HttpUtil)
3. REST 工具 (採用 RestTemplate, **USE:** RestTemplateUtil)
4. 驗證碼產生器 (**USE:** CaptchaUtil)
5. 隨機金鑰產生器 (**USE:** GenerateKeyUtil)
6. MD5 轉碼工具 (**USE:** MD5Util)
7. File 工具 (**USE:** FileUtil)
8. Hex 轉碼工具 (**USE:** HexUtil)
9. JSON 轉換工具 (**USE:** JsonUtil)
10. Log 工具 (採用 spring-boot-starter-logging, **USE:** Log)
11. Object 工具 (用於 Pojo 屬性複製, **USE:** PojoUtil)
13. 加解密工具 (AES 128 & RSA 2048, **USE:** AESUtil, RSAUtil)
14. JWT Token 工具 (採用 jjwt 0.9.1, **USE:** JwtUtil)
15. 字串壓縮工具 (**USE:** GzipStrUtil)
16. Date Deserializer (**USE:** @JsonDeserialize(using = DateDeserializer.class), @JsonDeserialize(contentUsing=DateDeserializer.class))
17. Date Serializer (**USE:** @JsonSerialize(using = JsonDateSerializer.class))
20. SwaggerCreater (**USE:** SwaggerCreater)
21. 獲得 Client IP (**USE:** IpUtils)
22. 紀錄 Client IP 的攔截器 (**USE:** IpInterceptor)
23. 確認 user 登入狀態攔截器 (**USE:** UserInterceptor - redisTemplate, whiteList)
