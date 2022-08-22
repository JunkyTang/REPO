# REPO


## 添加tag

```
git tag -a tag-name

git tag -d tag-name
git push origin :refs/tags/tag-name
```

## 验证 spec

```
pod spec lint --allow-warnings
```

## 提交

```
pod repo push JKRepo lib_name.podspec --allow-warnings
```
