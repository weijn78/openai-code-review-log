```json
{
  "issues": [
    {
      "file_path": "openai-code-review-test/src/main/java/cn/weijn/test/test3.java",
      "line_number": 17,
      "issue_type": "Code规范性",
      "severity": 2,
      "description": "在打印输出中使用了数字1，可能会造成误解，应该去掉前缀的1。",
      "suggestion": "将输出语句中的 '1' 移除，改为 '斐波那契数列第' + n + '项为：' + fib(n);"
    }
  ]
}
```