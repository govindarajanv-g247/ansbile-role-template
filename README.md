# ansbile-role-template

The file requirements.yml can contain the following

```yaml
---
# from galaxy
    - name: cielito.system

 from locally cloned git repository (git+file:// requires full paths)
    - src: git+file:///home/bennojoy/nginx

 from GitHub, overriding the name and specifying a specific tag
    - name: nginx_role
      src: https://github.com/bennojoy/nginx
      version: main
```
