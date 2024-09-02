# Month 03 工作报告 24/08/01-24/08/30

## RuyiSDK

+ 为 ruyi-mugen 添加新的 ruyi_test_wps_i18n [测试用例](https://github.com/delete-cloud/ruyi-mugen/blob/ruyi-i18n/testcases/cli-test/ruyi/ruyi_test_wps_i18n/ruyi_test_wps_i18n.sh) (存在问题)
  + wps install i18n test 测试用例 设计思路：
  + 分为三种情况运行 ruyi install --host x86_64 wps-office (1. 未下载 wps deb 包至对应目录 2. 下载 wps deb 包至对应目录并正常安装 3. 已安装后再次运行安装命令)  并捕获控制台输出以匹配部分关键词，检测不同 locale 下控制台的输出
  + 其中 locale 的更改方式为使用 jq 工具对 [config.json](https://github.com/delete-cloud/ruyi-mugen/blob/ruyi-i18n/testcases/cli-test/ruyi/ruyi_test_wps_i18n/config.json) 进行解析并加载
  + i18n 方面使用 GNU gettext，人工确定检测匹配的关键词，并使用 gettext 对关键词进行包裹，生成 .pot 模版文件，并通过 .pot 文件生成对应 locales 的 .po 文件(对人友好，可读)，.mo 文件(二进制文件，计算机使用)，不同 locale 下匹配对应 locale 的关键词

gettext 参考资料：[Translating apps with gettext: A comprehensive tutorial - Lokalise Blog](https://lokalise.com/blog/translating-apps-with-gettext-comprehensive-tutorial/)

## openQA

+ 设计 gedit needles 用例，并通过测试，上传 [用例](https://github.com/delete-cloud/openqa-test/tree/main/needles/gedit) 与 [测试结果](https://github.com/delete-cloud/openqa-test/tree/main/test-result/gedit)
+ 汇总优化 openQA 平台时遇到的一些 [问题](https://github.com/delete-cloud/openqa-test/blob/main/problem.md)
