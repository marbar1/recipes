
Run hugo server from a GitHub codespace
```
hugo server -D --appendPort=false --baseURL https://${CODESPACE_NAME}-1313.${GITHUB_CODESPACES_PORT_FORWARDING_DOMAIN}
```