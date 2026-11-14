# easySSL

easySSL keeps TLS certificates issued, renewed and installed on your hosts. The Server requests each Certificate over ACME, validated through a one-time DNS delegation, and renews it on schedule. An Agent on each host installs it where nginx, Apache or any other program reads it, through Plugins.

The parts that run on your hosts are published here, so they can be inspected and audited:

- [easyssl-agent](https://github.com/easyssl-io/easyssl-agent): the Agent, under FSL-1.1-ALv2.
- [easyssl-plugins](https://github.com/easyssl-io/easyssl-plugins): the first-party Plugins, under Apache-2.0.
- [easyssl-contract](https://github.com/easyssl-io/easyssl-contract): the contracts between the Server, the Agent and the Plugins, under Apache-2.0.

http://easyssl.io/
