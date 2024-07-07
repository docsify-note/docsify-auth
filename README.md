# docsify-auth
a auth pulign for docsify

![](./demo.png)

## Usage

1. Configure docsify-auth:(配置)

    ```html
    <script>
    window.$docsify = {
      // auth
      auth: {
        enable: true, // 是否开启
        password: "e10adc3949ba59abbe56e057f20f883e", // md5密码
        title: "请输入密码以访问文档：", // 设置标题
        paths: ["^/bookmark"] // 需要认证的路径，支持正则表达式匹配
      }
    }
    </script>
    ```

2. Insert script into docsify document:

    ```html

    <!-- body -->
    <script src="https://unpkg.com/docsify-auto@1.0.0/dist/docsify-auth.min.js"></script>
