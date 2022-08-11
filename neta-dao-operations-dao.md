# Overview

Neta DAO Operations handles the costs incurred by supporting the Neta DAO. Currently those include paying our validator costs, domain name and Akash hosting needs.

Address: juno1excmamnysxujtd2hzm343nzdwch79y5cvk5h7w6uxlrt230xqwtqkmancl [Link](https://daodao.zone/dao/juno1excmamnysxujtd2hzm343nzdwch79y5cvk5h7w6uxlrt230xqwtqkmancl)

## Member Composition

- massv (Neta DAO): juno1fzw7lp3u708rg49zqv48pdm8e03uz4srw2dx39 | [Verification](https://juno.tools/sign-verify?address=juno1fzw7lp3u708rg49zqv48pdm8e03uz4srw2dx39&message=Massv+was+here&signature=Oe%2BmHpM1horX1OOYVxc7AyjOYwjGqiXK4bMVOd1K2xNTIjKxC2xdC9q8QANG5QB%2BoVd7ETna7ei0VjZzy2YU0Q%3D%3D)  
- wtrsld (Neta DAO): juno1e6fhmfer34hh7kl9um6p52nkqflkp4jajgxunw | [Verification](https://juno.tools/sign-verify/?address=juno1e6fhmfer34hh7kl9um6p52nkqflkp4jajgxunw&message=Idols%20are%20coming...&signature=lFrRpDytImtZjokuQSwT9aYFLYnVi2h6%2BMouxCjivc8taxsVmprz7Bp9DOoEqmsLD%2FjvF0ZbymaTBqN4HLurqQ%3D%3D)  
- envy (Neta DAO): juno1g5t9r670acafp8ys3zpd5dxzunv99l3t6ruq9r | [Verification](https://juno.tools/sign-verify?address=juno1g5t9r670acafp8ys3zpd5dxzunv99l3t6ruq9r&message=envy9950&signature=9DNRtJvOmQFi9RhJTFCH2popSonjmFhkswLWYkGbc8xHOhngrAUYDfEBSDBDkh0nNckpJmWZjH6xMDKmLvhjDQ==)  
- whiskey (Neta DAO): juno1hcqjney83mcm50jvf70lk3h6yytkke0x98czhz | [Verification](https://juno.tools/sign-verify?address=juno1hcqjney83mcm50jvf70lk3h6yytkke0x98czhz&message=onewhiskeypls&signature=Q18qNlrODmZyUqMExCInD5Kfh%2B0RxuPinGgomPWgf0Zr7N7cBc3Fy1iSsy0R%2Ft6%2BlfCY%2F3QEvZ0%2BddxQLPCVsQ%3D%3D)  
- dude from internet (Neta DAO): juno1dpn437a94w9hktdw38zwuu7dtj22f6l4vce8r4 | [Verification](https://juno.tools/sign-verify/?address=juno15jxj5tcfqwnmupfzleuxaqfqvyjkjvd35vdea9&message=dude%20from%20internet.idols%232140&signature=I4y%2FIS87LOTwwUvMhZyHk8FsJ%2F9hWJ7TegpW0DMaeWo5LJxlQ%2FMuiA3sn0uI95RxhFBdouPgAk8dfxxBdnJwDQ%3D%3D)  

## Instantiation Message
```json
{
  "admin": null,
  "automatically_add_cw20s": true,
  "automatically_add_cw721s": true,
  "description": "Neta DAO Operations handles the costs incurred by supporting the Neta DAO. Currently those include paying our validator costs, domain name and Akash hosting needs. https://github.com/netadao/organizational-docs/blob/main/neta-dao-operations-dao.md",
  "image_url": "https://github.com/netadao/organizational-docs/blob/main/assets/NetaDAO_Operations_Logo.png?raw=true",
  "name": "Neta DAO Operations",
  "proposal_modules_instantiate_info": [
    {
      "admin": {
        "core_contract": {}
      },
      "code_id": 427,
      "label": "DAO_Neta DAO Operations_cw-proposal-single",
      "msg": {
        "allow_revoting": false,
        "deposit_info": null,
        "max_voting_period": {
          "time": 432000
        },
        "only_members_execute": true,
        "threshold": {
          "absolute_percentage": {
            "percentage": {
              "percent": "0.60"
            }
          }
        }
      }
    }
  ],
  "voting_module_instantiate_info": {
    "admin": {
      "core_contract": {}
    },
    "code_id": 429,
    "label": "DAO_Neta DAO Operations_cw4-voting",
    "msg": {
      "cw4_group_code_id": 434,
      "initial_members": [
        {
          "addr": "juno1hcqjney83mcm50jvf70lk3h6yytkke0x98czhz",
          "weight": 1
        },
        {
          "addr": "juno1fzw7lp3u708rg49zqv48pdm8e03uz4srw2dx39",
          "weight": 1
        },
        {
          "addr": "juno1e6fhmfer34hh7kl9um6p52nkqflkp4jajgxunw",
          "weight": 1
        },
        {
          "addr": "juno1g5t9r670acafp8ys3zpd5dxzunv99l3t6ruq9r",
          "weight": 1
        },
        {
          "addr": "juno1dpn437a94w9hktdw38zwuu7dtj22f6l4vce8r4",
          "weight": 1
        }
      ]
    }
  }
}
```
