# Ansible Role: Grafana

This role installs and configures Grafana - for analytics and monitoring.

It has only been designed to work on Ubuntu 16.04, but other Debian flavours
should also work.


## Requirements

None.


## Role Variables

TODO


## Resources

Documentation related to Grafana can be found at the links below:

- [documentation](http://docs.grafana.org/)


## Dependencies

None, but you may want to run grafana behind a webserver - I recommend using the
[geerlingguy.nginx](https://github.com/geerlingguy/ansible-role-nginx) role.


## Example Playbook

```yaml
- hosts: servers
  become: yes

  roles:
    - role: jradtilbrook.grafana
```


## License

MIT
