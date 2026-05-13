# 操作系统

## 🎯 生存指南
> 核心就三件事：**进程同步、内存管理、文件系统**。实验是难点，建议大一开始跟哈工大MOOC，linux-0.11实验做完就通了。不要死磕理论，先跑通实验再回头看书。

## 📺 视频课程
- **哈工大《操作系统》**: https://mooc.study.163.com/course/1000002004 — 四大模块，实验驱动
- 中国大学MOOC搜索"操作系统 北京大学" — 陈向群经典课
- B站搜索"清华大学 操作系统" — 多版本可选
- **MIT 6.828**: https://pdos.csail.mit.edu/6.828/2018/schedule.html — 研究生硬核
- **MIT 6.S081**: https://pdos.csail.mit.edu/6.S081/2020/schedule.html — 本科级别

## 📖 免费教材
- **OSTEP**: https://pages.cs.wisc.edu/~remzi/OSTEP/ — 免费在线操作系统圣经（英文）

## 🔧 实验资源
- **ucore OS Labs**: https://github.com/chyyuu/ucore_lab — 清华操作系统实验
- **HIT-OSLab**: https://github.com/hoverwinter/HIT-OSLab — 哈工大满分实验代码
- **xv6源码**: https://github.com/mit-pdos/xv6-riscv — MIT教学OS
- **Linux内核浏览**: https://elixir.bootlin.com/linux/latest/source

## 📋 最短学习路径
1. 进程/线程管理（创建、调度PV操作）— 2周
2. 内存管理（分页、虚拟内存、页面置换）— 1.5周
3. 文件系统（索引节点、磁盘调度）— 1周
4. 死锁（银行家算法）— 3天
5. 开始做实验（从lab1开始）

⚠️ **避坑**：不要只看视频不动手！实验至少要独立完成3个。考试重点在进程同步和内存管理。推荐路线：哈工大MOOC → ucore实验 → MIT 6.S081进阶。

## 💬 社区求助
- Stack Overflow: https://stackoverflow.com/questions/tagged/operating-system
- 知乎话题: 搜索"操作系统"