# MJClassInfo
类底层结构整理，导入后可直接使用，引入的类.m需改成.mm
  使用示例：    
    uint32_t flags = ((__bridge struct mj_objc_class *)cls)->data()->flags;
