repos:
  - repo: https://github.com/mercadolibre/fury_websec-git-hooks
    rev: v1.0.1
    hooks:
      - id: pre_commit_hook
        stages: [commit]
      - id: post_commit_hook
        stages: [post-commit]
