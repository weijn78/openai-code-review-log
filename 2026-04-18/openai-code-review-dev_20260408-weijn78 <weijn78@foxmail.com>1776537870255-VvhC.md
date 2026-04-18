```json
{
  "issues": [
    {
      "file_path": "openai-code-review-sdk/pom.xml",
      "line_number": 73,
      "issue_type": "Security Vulnerability",
      "severity": 3,
      "description": "Hardcoded database credentials in pom.xml file.",
      "suggestion": "Remove hardcoded credentials from pom.xml and use environment variables or configuration files to manage them."
    },
    {
      "file_path": "openai-code-review-sdk/src/main/java/cn/weijn/sdk/OpenAiCodeReview.java",
      "line_number": 57,
      "issue_type": "Security Vulnerability",
      "severity": 3,
      "description": "Hardcoded database credentials in the code.",
      "suggestion": "Remove hardcoded credentials from the code and use environment variables or configuration files to manage them."
    },
    {
      "file_path": "openai-code-review-sdk/src/main/java/cn/weijn/sdk/OpenAiCodeReview.java",
      "line_number": 61,
      "issue_type": "Resource Management",
      "severity": 2,
      "description": "Database connection not closed properly.",
      "suggestion": "Ensure that database connections are closed properly after use to avoid potential resource leaks."
    },
    {
      "file_path": "openai-code-review-sdk/src/main/java/cn/weijn/sdk/OpenAiCodeReview.java",
      "line_number": 64,
      "issue_type": "Security Vulnerability",
      "severity": 3,
      "description": "Hardcoded database credentials in the code.",
      "suggestion": "Remove hardcoded credentials from the code and use environment variables or configuration files to manage them."
    },
    {
      "file_path": "openai-code-review-sdk/src/main/java/cn/weijn/sdk/OpenAiCodeReview.java",
      "line_number": 68,
      "issue_type": "Code Duplication",
      "severity": 2,
      "description": "Code duplication in getEnvOptional and getEnvLongOptional methods.",
      "suggestion": "Merge these methods into a single method to reduce code duplication."
    },
    {
      "file_path": "openai-code-review-sdk/src/main/java/cn/weijn/sdk/infrastructure/git/GitCommand.java",
      "line_number": 47,
      "issue_type": "Concurrency",
      "severity": 2,
      "description": "Static variable latestCommitHash may be accessed concurrently without synchronization.",
      "suggestion": "Synchronize access to the static variable latestCommitHash if it is accessed from multiple threads."
    }
  ]
}
```