<div align="center">
  <a href="https://privacysafe.is">
    <img src="https://raw.githubusercontent.com/PrivacySafe/privacysafe-search/master/client/simple/src/brand/searxng.svg" height="100" />
  </a>

  # PrivacySafe Search &ndash; Worry-Free Search Engine
</div>

[PrivacySafe Search](https://privacysafe.is) delivers results from various search engines while protecting you from tracking.  

**No filter bubbles. No surveillance. Just answers.**

Built on the open-source [SearXNG](https://github.com/searxng/searxng) metasearch engine and integrated with the [PrivacySafe](https://github.com/PrivacySafe) suite, this service is designed for users who value privacy and freedom by default.

> ⚠️ Currently in beta. Expect regular updates and improvements.

| Feature | Description |
|--------|-------------|
| 🌐 **82+ Aggregated Sources** | Combines results from multiple engines with no profiling. |
| 🕵️ **Tracker Removal** | Automatically strips ad trackers (e.g., `utm_`, `fbclid`) from all URLs. |
| 🏛️ **Web Archive View** | View cached pages via the Internet Archive. |
| 🌑 **Dark Mode by Default** | Sleek dark theme that's easy on the eyes. |
| 🧠 **Autocomplete** | Helpful suggestions to speed up your search. |
| 🔍 **Moderate SafeSearch** | Balanced filtering to keep results clean. Easy to toggle on/off. |
| 🧅 **Tor Circuit Check** | Lets Tor users know if their connection is secure and routed properly. |

## Deploy It Yourself

PrivacySafe Search is modified from [SearXNG](https://github.com/searxng/searxng) with some configuration tweaks and PrivacySafe-specific defaults. If you’re not part of the PrivacySafe ecosystem or just want your own private search instance, we recommend deploying SearXNG using one of these options: 

Deployment options:

- **[Docker](https://github.com/searxng/searxng-docker)** – includes support for ARM64 and ARMv7
- **[Install Scripts](https://docs.searxng.org/admin/installation-scripts.html)** – for automatic setup
- **[Manual Installation](https://docs.searxng.org/admin/installation-searxng.html)** – if you want to customize everything
- **[Admin Docs](https://docs.searxng.org/admin/)** – for all configuration and performance tuning

For PrivacySafe users, our hosted version integrates with [RefreshView](https://refreshview.com), [PrivacySafe Social](https://privacysafe.social), and more.

## Contributing

We welcome developers, tinkerers, and privacy geeks.  
Fork us and start hacking:

```bash
git clone https://github.com/PrivacySafe/privacysafe-search.git
cd privacysafe-search
make run
```

See the [SearXNG Dev Quickstart](https://docs.searxng.org/dev/quickstart.html) for details.

## License

© 2025–present PrivacySafe Services LLC. This project is dedicated to ethical <a href="https://fsf.org" target="_blank" rel="noreferrer noopener">Free and Open Source Software</a> and <a href="https://oshwa.org" target="_blank" rel="noreferrer noopener">Open Source Hardware</a>. PrivacySafe® is a registered trademark.

Released under the [GNU Affero General Public License v3.0 (AGPLv3)](LICENSE). See [LICENSE](LICENSE) for more information. PrivacySafe Search is based on [SearXNG](https://github.com/searxng/searxng), which is also licensed under AGPLv3.
