sa-inject-keys
==============

[![Build Status](https://travis-ci.org/softasap/sa-inject-keys.svg?branch=master)](https://travis-ci.org/softasap/sa-inject-keys)


Simple

  roles:
    - {
        role: "sa-inject-keys"
      }


Advanced:


  roles:
    - {
        role: "sa-inject-keys",
        keys: ["~/.ssh/id_rsa"],
        authorized_keys: ["~/.ssh/id_rsa.pub"]
      }
