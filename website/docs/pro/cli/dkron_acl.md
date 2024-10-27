---
date: 2024-10-06
title: "dkron acl"
slug: dkron_acl
url: /docs/pro/cli/dkron_acl/
---
## dkron acl

Control ACL policies

### Synopsis

Control ACL policies. This command allows to manage ACL policies.

### Options

```
      --cert-file string         Path to the client server TLS cert file
  -h, --help                     help for acl
      --key-file string          Path to the client server TLS key file
      --rpc-addr string          gRPC address of the agent (default "127.0.0.1:6868")
      --trusted-ca-file string   Path to the client server TLS trusted CA cert file
```

### Options inherited from parent commands

```
      --config string   config file (default is /etc/dkron/dkron.yml)
```

### SEE ALSO

* [dkron](/docs/pro/cli/dkron/)	 - Professional distributed job scheduling system
* [dkron acl bootstrap](/docs/pro/cli/dkron_acl_bootstrap/)	 - Bootstrap ACL policies
* [dkron acl policy](/docs/pro/cli/dkron_acl_policy/)	 - Operate ACL policies
* [dkron acl token](/docs/pro/cli/dkron_acl_token/)	 - Operate ACL tokens

###### Auto generated by spf13/cobra on 6-Oct-2024