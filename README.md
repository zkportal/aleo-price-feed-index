# Aleo price feed index for Aleo oracle

This repository is updated automatically to track Unix timestamps of price feed updates of ALEO, BTC, and ETH on Aleo blockchain.

The timestamps can be used together with request hashes to restore timestamped request hashes that are used to read historical price feed data from the mappings.

For more information see [https://docs.aleooracle.xyz](https://docs.aleooracle.xyz/guide/oracle_program/).

The history of price feed is stored in files of the following format: `<tee_type>_history_<coin>.txt`, e.g. `sgx_history_aleo.txt`.
