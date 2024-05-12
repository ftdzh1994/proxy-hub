# proxy-hub
this repository is used to store thing about proxy

## Usage
- rule路径 下维护自己需要的规则
- 先更新main, 再通过 clash verge 的覆盖脚本更新 dns。获取 dns 更新后的配置再保存
- 使用 https://nick.ftdzh1994.workers.dev 作为加速前缀下载配置文件

## To Do
- [ ] 测试为内网字段设置 nameserver-policy
- [ ] 设置tiktok免翻墙
- [ ] 通过github action 来执行更新dns?
- [x] 使用github加速


## Reference
- 分流规则
  - https://github.com/blackmatrix7/ios_rule_script
  - https://github.com/ACL4SSR/ACL4SSR/tree/master
  - https://github.com/lainbo/gists-hub
- github加速
  - 加速前缀： https://nick.ftdzh1994.workers.dev
  - [参考项目](https://github.com/hunshcn/gh-proxy)
- 参考
  - [最佳实践](https://lainbo.com/article/clash-config#651db62cc0554e8cb16b7c421bba08d5)
  - [stash用户文档](https://stash.wiki/)
  - [Clash.Meta用户文档](https://wiki.metacubex.one/)
  - [Clash.Meta 的 DNS 工作流程](https://wiki.metacubex.one/config/dns/diagram/)
  - [在 Clash 中 DNS 解析行为和 fallback-filter 的一点理解](https://cosey.me/p/clash-fallback-filter)