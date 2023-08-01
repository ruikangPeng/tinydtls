# CONTENTS

这个库包含的函数和结构可以帮助在 C99 中构建具有 DTLS 支持的单线程 UDP 服务器。
以下组件可用：

* dtls
  
  预共享密钥模式(pre-shared key mode)对 DTLS 的基本支持。

* tests
  
  子目录 tests 包含显示如何使用每个组件的测试程序。

# BUILDING

当使用 git 存储库中的代码时，调用 make 将 DTLS 构建为共享库。
