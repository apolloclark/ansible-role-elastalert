# Ansible Role: elastalert

Ansible Role to install and configure Yelp/elastalert


## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`).
You can overload the variables by creating a dictionary called "elastalert", ex:

    elastalert:
      output: "json"


## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.elastalert

## License

MIT / BSD

## Author Information

This role was created in 2019 by [Apollo Clark](https://www.apolloclark.com/)
