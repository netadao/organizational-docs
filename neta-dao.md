# Overview

Neta DAO. The Community Accelerator - Funding collaboration, growth and innovation around $NETA. For more info visit https://netadao.zone/

Address: juno1c5v6jkmre5xa9vf9aas6yxewc7aqmjy0rlkkyk4d88pnwuhclyhsrhhns6 [LINK](https://daodao.zone/dao/juno1c5v6jkmre5xa9vf9aas6yxewc7aqmjy0rlkkyk4d88pnwuhclyhsrhhns6)

## Instantiation Message

```json

{
  "admin": null,
  "automatically_add_cw20s": true,
  "automatically_add_cw721s": true,
  "description": "Neta DAO. The Community Accelerator - Funding collaboration, growth and innovation around $NETA. For more info visit https://netadao.zone/",
  "image_url": "https://github.com/netadao/organizational-docs/blob/main/assets/NetaDAO_Logo.png?raw=true",
  "name": "Neta DAO",
  "proposal_modules_instantiate_info": [
    {
      "admin": {
        "core_contract": {}
      },
      "code_id": 627,
      "label": "DAO_Neta DAO_cw-proposal-single",
      "msg": {
        "allow_revoting": true,
        "deposit_info": {
          "deposit": "15000000",
          "refund_failed_proposals": false,
          "token": {
            "voting_module_token": {}
          }
        },
        "max_voting_period": {
          "time": 432000
        },
        "only_members_execute": true,
        "threshold": {
          "threshold_quorum": {
            "quorum": {
              "percent": "0.10"
            },
            "threshold": {
              "majority": {}
            }
          }
        },
        "executor_addr": "juno1zt8zwtpu0qy8tqdyz3knzlqe8q806n8zwgrasln4knlwkt6qllmqg9zzkk"
      }
    }
  ],
  "voting_module_instantiate_info": {
    "admin": {
      "core_contract": {}
    },
    "code_id": 431,
    "label": "DAO_Neta DAO_cw20-staked-balance-voting",
    "msg": {
      "token_info": {
        "existing": {
          "address": "juno168ctmpyppk90d34p3jjy658zf5a5l3w8wk35wht6ccqj4mr0yv8s4j5awr",
          "staking_contract": {
            "new": {
              "staking_code_id": 430,
              "unstaking_duration": {
                "time": 7862400
              }
            }
          }
        }
      }
    }
  }
}

```
