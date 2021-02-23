## Install alpha release of kapp-controller

The alpha release of kapp-controller contains the packaging APIs, which are undergoing active development. The alpha release should only 
be used for experimenting with the packaging APIs as there will be possible breaking changes as further feedback is collected.

To install with `kapp`:

```bash
$ kapp deploy -a kc -f https://raw.githubusercontent.com/vmware-tanzu/carvel-kapp-controller/dev-packaging/alpha-releases/v0.17.0-alpha.1.yml
```

To install with `kubectl`:

```bash
kubectl apply -f https://raw.githubusercontent.com/vmware-tanzu/carvel-kapp-controller/dev-packaging/alpha-releases/v0.17.0-alpha.1.yml
```
