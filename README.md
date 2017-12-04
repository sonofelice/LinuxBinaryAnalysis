# LinuxBinaryAnalysis
本仓库用于《Linux二进制分析》中文版的勘误提交以及发布。

勘误格式如下：
```

P69，第35行，印次1， 应改为：
h.phdr = (Elf64_Phdr *)(h.mem + h.ehdr->e_phoff);

```
