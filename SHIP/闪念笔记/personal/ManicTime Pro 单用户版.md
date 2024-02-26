---
link: https://www.notion.so/ManicTime-Pro-627c1f68949c4ed2845eb52799f98af0
notionID: 627c1f68-949c-4ed2-845e-b52799f98af0
---
| <p style="text-align:center;margin:0">ManicTime Pro 单用户版</p> |
| -- |
| <span style="font-family:.PingFangSC-Regular;">授权名</span>: zhiyuan yu |
| <span style="font-family:.PingFangSC-Regular;">邮箱</span>: <a href="mailto:1072710413@qq.com" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;"><u>1072710413@qq.com</u></a> |
| <span style="font-family:.PingFangSC-Regular;">授权码</span>: WBJV-KXMF-UXBU-78TN-K3L8-HLVT-F46Z-8MS8-Z95Y-LP2U-M5ZU-4HR4-CNZN-DYCH-D9Z5-N4G3 |




docker run -v /var/lib/manictimeserver/Data:/app/Data -p 8080:8080 manictime/manictimeserver


Setup.dll -publicurl
ManicTime Server 2023.3.1.1 setup started.
warn: Microsoft.AspNetCore.DataProtection.Repositories.FileSystemXmlRepository[60]
      Storing keys in a directory '/root/.aspnet/DataProtection-Keys' that may not be persisted outside of the container. Protected data will be unavailable when container is destroyed.
warn: Microsoft.AspNetCore.DataProtection.KeyManagement.XmlKeyManager[35]
      No XML encryptor configured. Key {7c7336ad-9415-4642-b0e9-050aa0210efa} may be persisted to storage in unencrypted form.
Listening on: http://localhost:8080/33ffe985f2d9453a81bb3da64be4bac2
Press Ctrl+C to stop.



docker run -v /var/lib/manictimeserver/Data:/app/Data --rm --entrypoint dotnet  manictime/manictimeserver ManicTimeServer.dll 

addadmin -u 1072710413@qq.com -p yuzhiyuan123