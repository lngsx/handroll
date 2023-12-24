# ¯\(ツ)/¯

Install `ansible` and then 

Do this...

```bash
ansible-pull --url https://github.com/lngsx/handroll do_me.yml --extra-vars "human=$(whoami)" --ask-become-pass --verbose
```

Or this

```bash
ansible-playbook do_me.yml --extra-vars "human=$(whoami)" --ask-become-pass --verbose
```
