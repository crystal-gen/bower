```yaml
name: bower-test
version: 0.1.0

generators:
  bower:
    spec:
      analytics: true
      ca: true
      cwd: '~/my-project'
      directory: '~/my-project/vendor'
      registry_search:
        - 'http://localhost:8000'
      registry_register: 'http://localhost:8000'
      registry_publish: 'http://localhost:8000'
      shorthand-resolver: 'git://example.com/{{shorthand}}.git'
      proxy: 'http://localhost:8080'
      https-proxy: 'https://localhost:8081'
      user-agent: 'Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36'
      timeout: 40000
      strict-ssl: false
      ca: '/etc/ssl/cert.pem'
      color: true
      storage_cache: '~/.bower/cache'
      storage_registry: '~/.bower/registry'
      tmp: '~/.bower/tmp'
      interactive: true
    version: latest
```