# OctusBridge deploy guide
=========

This is complete guide to deploy all things needed for fully EVM<->Everscale bridge which able to transfer ERC and TIP-3 tokens.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

1. Ubuntu on deploy machines, Tested on 22.04, but should work at other versions too.
2. Instance for

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

1. Python and Ansible to use ansible scripts
2. Scripts are not tested on Windows, so I assume Linux.
3. Install ansible dependencies with "ansible-galaxy install -r requirements.yml"

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.


License
-------

BSD

My links
------------------

[AntonIXO](https://github.com/AntonIXO)
[Telegram](https://t.me/antonlx)

devpins.eth
Everscale: 0:c7a049f582425eb44408894b9bec7adc072adc4286121c9636aa3562d3948f48
