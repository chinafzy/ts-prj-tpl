# ts project template

这个是一个 `typescript` 的项目模板。

参考于牛逼闪闪的 `ts-jest`

## 使用

快速上手

+ 安装依赖 `yarn install`
+ 运行测试代码 `yarn test`
+ 运行构建 `yarn build`
+ 清理构建 `yarn clear`
+ [建议] 代码格式检查 `yarn eslint`
+ [建议] 代码格式修复 `yarn eslint-fix`

## 项目说明

### 目录结构

+ src 源码位置，一般情况下只需要关注这个目录
+ dist 编译后生成的目录

### 一定要写unit test

unit test是报障代码质量的最简单有效方式，每次写一点功能，最好都要加上对应的测试函数，来验证自己的正确和失误。

将测试代码放在源码一起是个好的管理方式。比如源文件是 `lib1.ts`，测试代码就是`lib1.spec.ts`，使用命令来测试 `yarn test lib1.spec.ts`。

同时测试代码也就可以作为功能范例和使用说明。

### 为什么要代码格式化

长期的项目，规范是非常重要的。包括代码风格，编码规范。尤其是nodejs项目，大家各自有不同的习惯，对于长期项目来说就会有个麻烦。
