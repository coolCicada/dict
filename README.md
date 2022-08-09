# 数据字典库

## 1 api使用
- 显示：getDictValue('dictName', value);
- 获取：getDict

## 2 实现
- getDictValue 
  - 传入this (vue组件)
  - 如果需要发送请求则修改this 的某个属性 （loading）
  - 请求返回 缓存字典，重置loading