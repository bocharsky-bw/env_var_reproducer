# env_var_reproducer

To load website in `prod` environment using Symfony Web Server:

```bash
APP_ENV=prod bin/console s:r
```

Or use any other environment you want instead of `prod`.

To load website in a default dev environment, you even don't need to prepend env var, i.e:

```bash
bin/console s:r
```
