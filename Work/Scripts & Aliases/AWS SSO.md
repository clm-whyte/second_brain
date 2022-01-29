```
export AWS_DEFAULT_PROFILE=default
aws sso login
export AWS_DEFAULT_PROFILE=engineering
ut_ecs post-test-nightly bash
```