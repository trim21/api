非浏览器的 API 使用者请指定一个带有**个人 ID**和**应用名称**的 User Agent。

如果你的应用需要进行分发（如安卓客户端，或者某个语言的 SDK），请再附上**版本号**

如果你应用是一个开源项目，请在 User Agent 附上项目主页。

各种请求库的默认 UA 可能会被禁用。

建议的 User Agent 比如：

- `czy0729/Bangumi/6.4.0 (Android) (http://github.com/czy0729/Bangumi)`: 移动端 APP，请添加版本号。
- `trim21/bangumi-episode-ics (https://github.com/Trim21/bangumi-episode-calendar)`：cloudflare workers，不需要进行分发，可以不需要添加版本号。
- `sai/my-private-project`：某人的私有项目。

**请不要使用 "database"，"Bangumi/1.0"，"Bangumi/1.0.0.0"，"Bangumi/1.3.13.0" 等类似的 User Agent。**