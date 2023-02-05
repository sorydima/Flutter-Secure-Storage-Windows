# Flutter Secure Storage Windows

A fake drop-in replacement for [flutter_secure_storage](https://github.com/mogol/flutter_secure_storage/tree/develop/flutter_secure_storage_windows) in order to workaround https://gitlab.com/gitlab-com/gl-infra/reliability/-/issues/15161.

### Usage:

Add to pubspec.yaml

```yaml
dependency_overrides:
    flutter_secure_storage_windows:
        git:
            url: https://gitlab.com/TheOneWithTheBraid/flutter_secure_storage_windows.git
            ref: main
```
