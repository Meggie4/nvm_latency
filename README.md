# nvm_latency
现在需要对NVM的读写延迟进行设置，拷贝latency.h文件到/usr/src/linux-4.17.19/drivers/nvdimm目录下
同时更改pmem.c文件，include头文件latency.h 并按照亚博注释了ayu的地方进行修改。
