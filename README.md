# Flux Image Automation Demo

## Bootstrap

```
flux bootstrap github \
  --owner=relu \
  --repository=flux-demo \
  --path=clusters/local-kind \
  --personal \
  --token-auth \
  --components-extra=image-reflector-controller,image-automation-controller
```

## References

* [Installation](https://fluxcd.io/docs/guides/installation/)
* [Automate image updates to Git](https://fluxcd.io/docs/guides/image-update/)
* [How to make sortable image tags to use with automation](https://fluxcd.io/docs/guides/sortable-image-tags/)
