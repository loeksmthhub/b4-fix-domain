
## 部署:
* server.js 第 1、2 行修改页面访问的用户名和密码

  | 变量名        | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | WEB_USERNAME | 是 | admin | 网页的用户名 |
  | WEB_PASSWORD | 是 | password | 网页的密码 |

* entrypoint.sh 第 4-12 行设置各变量，如果不需要哪吒，删除或注释 6-8 行

  | 变量名        | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | UUID         | 否 | de04add9-5c68-8bab-950c-08cd5320df18 | 可在线生成 https://www.zxgj.cn/g/uuid |
  | WSPATH       | 否 | argo | 勿以 / 开头，各协议路径为 `/WSPATH-协议`，如 `/argo-vless`,`/argo-vmess`,`/argo-trojan`,`/argo-shadowsocks` |
  | NEZHA_SERVER | 否 |        | 哪吒探针服务端的 IP 或域名 |
  | NEZHA_PORT   | 否 |        | 哪吒探针服务端的端口 |
  | NEZHA_KEY    | 否 |        | 哪吒探针客户端专用 Key |
  | ARGO_AUTH    | 否 |        | Argo 的 Token 或者 json 值 |
  | ARGO_DOMAIN  | 否 |        | Argo 的域名，须与 ARGO_DOMAIN 必需一起填了才能生效 |

* 需要应用的 js
  | 命令 | 说明 |
  | ---- |------ |
  | <URL>/list | 查看节点数据 |
  | <URL>/status | 查看后台进程 |
  | <URL>/listen | 查看后台监听端口 |

<img width="1600" alt="image" src="https://user-images.githubusercontent.com/92626977/216796019-15e46823-c7b0-4a11-8128-31722e1bb76f.png">

<img width="1201" alt="image" src="https://user-images.githubusercontent.com/92626977/216796097-6613030d-92b2-4472-b341-83abe4674b40.png">

<img width="1090" alt="image" src="https://user-images.githubusercontent.com/92626977/221387459-30871976-7032-4993-9c46-244bdec7dc89.png">

<img width="1428" alt="image" src="https://user-images.githubusercontent.com/92626977/218391090-c75f5d7c-7d9a-4112-ac4d-d2773d23a737.png">

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/92626977/216795556-37b51817-6971-4eee-980e-f96588ee04d7.png">

<img width="966" alt="image" src="https://user-images.githubusercontent.com/92626977/216795892-f5fea4b4-680b-4ddd-8531-3e4af8bfa030.png">

<img width="732" alt="image" src="https://user-images.githubusercontent.com/92626977/216795939-f58d663d-adad-4088-8898-ad271c24e762.png">

<img width="499" alt="image" src="https://user-images.githubusercontent.com/92626977/212470733-446938ae-e403-424b-b7ce-51e775b30ed2.png">
