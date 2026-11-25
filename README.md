# hongguo-warm-rules

红果短剧·暖白版 的解析规则包。`rules.json` 由 `rules.json.sig.b64`（Ed25519 签名，base64）保护。
App 会从 `https://raw.githubusercontent.com/wxhwdg/hongguo-warm-rules/main/` 拉取这两个文件并验签。

字段：version / routes(get,post,get_renew,post_retry) / budget_ms / single_attempts / guest_fallback / quality_aliases
