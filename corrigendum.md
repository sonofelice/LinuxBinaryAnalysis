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
