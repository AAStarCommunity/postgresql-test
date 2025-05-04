# supabase test tool

you have a db connection url:

```
postgresql://usename:password@hostname:port/defaultDb
```

like this from supabase:

```
postgresql://postgres.rxuonwgooconbnqyhxbw:password@aws-0-ap-southeast-1.pooler.supabase.com:5432/postgres

```

## Supabase 客户端库说明
当我说"最好使用其提供的客户端库，它内置了安全机制"时，是指 Supabase 提供了官方的客户端 SDK，这些 SDK 具有以下优势：

内置认证：自动处理 JWT 令牌和会话管理
行级安全：与 Supabase 的行级安全规则无缝集成
实时更新：支持实时数据订阅
类型安全：提供了 TypeScript 类型定义
预配置的多个 API: 不仅是数据库，还包括存储、认证和函数等功能

Node.js/JavaScript SDK
Supabase 提供了多个 JavaScript 包：
bash# 主要客户端包（浏览器和 Node.js）
npm install @supabase/supabase-js

仅服务器端 Node.js 应用的轻量级包
npm install @supabase/postgrest-js
Go 语言 SDK
是的，Supabase 也提供了 Go 语言的官方 SDK：
bash# 使用 go get 安装
go get github.com/supabase/supabase-go
其他常用 SDK：

Python: pip install supabase
Rust: cargo add supabase-rust
Swift: pod 'Supabase'
Kotlin: implementation("io.github.jan-tennert.supabase:supabase-kt:$version")
C#/.NET: dotnet add package supabase-csharp