### 收获

1. 由闭包生成的保存在内存中的字段，在单页面app中，除非进行刷新操作，否则将一直存在于内存中。而如果是多页面app，那么刷新或者跳转路由都将会清除掉这些字段。
