# Go Web 开发手册

> Go Web 开发手册：2019年第6期

大纲:


- 需求分析
- 模型设计
- 技术选型
	- Go
	- ORM
		- gorm
		- xorm
	- Web 框架
		- gin
		- beego
		- go-restful
		- echo
		- iris
		- ...
	- 原生库
	    - net/http
	    - template

- 项目结构设计
- 单功能开发
	- 参数验证
	    - 是否必须
	    - 类型
	        - 整型
	            - 大小
	            - 区间
	            - 默认
	        - 字符串
	            - 选项
	            - 默认
	        - 数组
	            - 长度
	- 获取资源
	- 更新资源
	- 删除资源
	- 新增资源

- 认证/鉴权
	- 权限：jwt

- Restful 风格设计
	- 路由
	- 响应信息
	- 错误码
- 构建
    - Makefile
- 版本管理
    - git
- 文档
	- Swagger
	- Markdown
	- Docsify
	- VuePress
- 测试
	- PostMan 接口测试
	- 单元测试
	- 性能测试
	- 代码覆盖率
	    - codecov
- 持续集成
	- travisCI

- 持续部署
	- Docker 镜像构建
	- 镜像启动
	- DaoCloud


---

@Author: 谢伟

@WeChat: wu_xiaoshen

@ZhiHu: [谢伟](https://www.zhihu.com/people/wu-xiao-shen-16/activities)

@BiliBili:[Wuxiaoshen](https://space.bilibili.com/10056291)