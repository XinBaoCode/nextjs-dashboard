# Next.js App Router Course - Starter

## 基础信息

* 学习链接: [NextJs中文教程](https://qufei1993.github.io/nextjs-learn-cn/)

* 在线预览网址效果：点击[Vercel链接](https://nextjs-dashboard-rho-lyart-20.vercel.app/dashboard)预览
  * 登入账号：`user@nextmail.com`
  * 密码： `123456`

## 一些注意事项

* 苹果`M系列`芯片,在运行的时候如果报与`bcrypt`(加密用的依赖)错,可以试试如下命令。

```bash
npm rebuild bcrypt --build-from-source
```

这将重新编译`bcrypt`模块以适应你的系统

* `.env`文件中的`AUTH_SECRET`变量是用来在`NextAuth`框架中进行验证必须的变量
