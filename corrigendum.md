1.页码：61 • 行数：1 • 印次 1
应改为：
```
user_regs_struct结构体多了个空格
```

2.页码：69 • 行数：35 • 印次 1
应改为：
```
h.phdr = (Elf64_Phdr *)(h.mem + h.ehdr->e_phoff);
h.shdr = (Elf64_Shdr *)(h.mem + h.ehdr->e_shoff);
```
3.页码：88 • 行数：21 • 印次 1
应改为：
```
unsigned long shellcode_size = f2 - f1;
```
4.页码：14 • 行数：19 • 印次 1
应改为：
```
uint32_t p_flags; (segment flags, I.E execute|read|write)
```
5.前言页码：3 • 行数：6 • 印次 1 
应改为：
```
第 8 章，ECFS —— 扩展核心文件快照技术，介绍 ECFS 这一用于进程内存取证分析的新开源产品。
```
