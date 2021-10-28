Minecraft Bungee Proxy
======================

Containerize & orchestrate Minecraft Bungee proxy servers in Kubernetes.

The released images are based on the [kamarad-app/minecraft-bungee](https://github.com/kamarad-coal/minecraft-bungee) container image.

## 🤝 Supporting

Kamarad Coal is a [Renoki Games.](https://github.com/renoki-games) subsidiary, made with ❤. Consider reaching out and supporting [Renoki Games.](https://github.com/renoki-games) and [Renoki Co.](https://github.com/renoki-co).

[<img src="https://c5.patreon.com/external/logo/become_a_patron_button.png" height="41" width="175" />](https://www.patreon.com/bePatron?u=10965171)

## 🚀 Installation

Install the Helm chart repository:

```bash
$ helm repo add kamarad https://helm.kamarad.app
$ helm repo update
```

Install the chart:

```bash
$ helm upgrade my-bungee-proxy-server \
    --install \
    --version=0.1.1 \
    kamarad/minecraft-bungee
```

Check `values.yaml` for additional available customizations.

## 🐛 Testing

Coming soon.

## 🤝 Contributing

Please see [CONTRIBUTING](../../CONTRIBUTING.md) for details.

## 🔒  Security

If you discover any security related issues, please email alex@renoki.org instead of using the issue tracker.

## 🎉 Credits

- [Alex Renoki](https://github.com/rennokki)
- [All Contributors](../../../../contributors)
