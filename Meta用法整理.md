# Meta用法整理

- **属性**

  - http-equiv，content：项目与http文件头，给浏览器回传一些信息
  - name，content：页面描述信息

- **name**

  - keywords

  - description

  - robots：引擎搜索方式

    > - all：文件和页面链接都被检索
    > - none：文件和页面链接都不被检索
    > - index：文件被检索
    > - follow：页面链接被检索
    > - noindex：文件不被检索
    > - nofollow：页面链接不被检索

  - author

  - generator：编辑器

  - revisit-after：重访

  - decorator：jsp中用sitemesh来自动加载一些不变的模块

    ---

  - viewport：移动浏览

    > - width=device-width,height
    > - initial-scale=1.0
    > - minimum-scale
    > - maximum-scale
    > - user-scalable:手动缩放,no,yes

    ---

  - format-detection：telephone，email=yes。识别页面的数字

  - renderer：content=“webkit”，启用360急速模式

  - mobile-agent: content="[xml|xhtml|html5];url="url",ur为PC对应的手机页面

- **http-euiqv** 

  - expires：GMT格式日期

  - pragma：缓存

  - refresh：content=“2；url=http://www.baidu.com”停留2秒跳转到新页面

  - set-cookie：GMT格式

  - window-target：打开窗口方式

    > content:_top, _blank, _self, _ parent;

  - content-type：字符集，charset

  - pics-label：网页rsac等级评定

  - page-enter：

  - page-exit：页面打开和关闭特效

  - x-ua-compatible：专门用于ie8

    > - ie=edge
    > - ie=ie6
    > - ie=ie7
    > - chrome=1,有GCF的启用webkit内核

  - cache-control：content=“no-siteapp”,防止百度转码