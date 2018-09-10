# nep5-test
Code test for a nep-5 token ico 

Following this [article](https://medium.com/proof-of-working/how-to-build-an-ico-on-neo-with-the-nex-ico-smart-contract-template-1beac1ff0afd)

Source code from [neonexchange Github page](https://github.com/neonexchange/neo-ico-template)

[CGAS Article](https://medium.com/neo-smart-economy/cgas-contract-mapping-of-gas-officially-launched-in-neo-mainnet-21c4253dd4a4)

## Useful commands:

build path/to/template/ico_template.py

import contract path/to/template/ico_template.avm 0710 05 True False

testinvoke script_hash deploy [] 

import token script_hash 

testinvoke script_hash mintTokens [] --attach-neo=5 

testinvoke script_hash balanceOf ['AK2nJJpJr6o664CWJKi1QRXjqeic2zRp8y'] 

testinvoke 6add70c2e1db8663e16c748e37ec9cad27530051 transfer ['AK2nJJpJr6o664CWJKi1QRXjqeic2zRp8y','AZaKGhAeFkAKC7zT2eorfgAkXdPaT48Tmo',1000]

import contract_addr script_hash 031a6c6fbbdf02ca351745fa86b9ba5a9452d785ac4f7fc2b7548ca2a46c4fcf4a 

send neo AK2nJJpJr6o664CWJKi1QRXjqeic2zRp8y 1 --from-addr=address

