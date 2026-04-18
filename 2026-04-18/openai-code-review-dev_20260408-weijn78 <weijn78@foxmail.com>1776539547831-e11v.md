```json
{
  "issues": [
    {
      "file_path": "openai-code-review-sdk/src/main/java/cn/weijn/sdk/OpenAiCodeReview.java",
      "line_number": 66,
      "issue_type": "Security Vulnerability",
      "severity": 3,
      "description": "Hardcoded database credentials are used.",
      "suggestion": "Avoid hardcoding sensitive information like database credentials. Use environment variables or configuration files."
    },
    {
      "file_path": "openai-code-review-test/src/main/java/cn/weijn/test/test3.java",
      "line_number": 15,
      "issue_type": "Code Readability",
      "severity": 2,
      "description": "String concatenation with variable interpolation is not clear.",
      "suggestion": "Use a more descriptive string format, such as String.format or StringBuilder."
    }
  ]
}
```