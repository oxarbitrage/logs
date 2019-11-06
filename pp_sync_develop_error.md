```
...
991488ms th_a       application.cpp:499           handle_block         ] Got block: #2380000 time: 2019-01-16T10:29:30 latency: 25418821488 ms from: nuevax-test  irreversible: 2379987 (-13)
991858ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T11:00:00
992780ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T12:00:00
993838ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T13:00:00
994704ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T14:00:00
995785ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T15:00:00
996609ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T16:00:00
997633ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T17:00:00
998411ms th_a       db_maint.cpp:1283             process_dividend_ass ] In process_dividend_assets time 2019-01-16T18:00:00
998916ms th_a       db_block.cpp:279              _push_block          ] Failed to push new block:
10 assert_exception: Assert Exception
maybe_found != nullptr: Unable to find Object
    {"id":"1.25.224"}
    th_a  index.hpp:113 get

    {"op":{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}}
    th_a  betting_market_evaluator.cpp:312 do_evaluate

    {}
    th_a  evaluator.cpp:51 start_evaluate

    {"op":[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]}
    th_a  db_block.cpp:780 apply_operation

    {"trx":{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"]}}
    th_a  db_block.cpp:766 _apply_transaction

    {"next_block.block_num()":2389738}
    th_a  db_block.cpp:662 _apply_block
998916ms th_a       application.cpp:531           handle_block         ] Error when pushing block:
10 assert_exception: Assert Exception
maybe_found != nullptr: Unable to find Object
    {"id":"1.25.224"}
    th_a  index.hpp:113 get

    {"op":{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}}
    th_a  betting_market_evaluator.cpp:312 do_evaluate

    {}
    th_a  evaluator.cpp:51 start_evaluate

    {"op":[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]}
    th_a  db_block.cpp:780 apply_operation

    {"trx":{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"]}}
    th_a  db_block.cpp:766 _apply_transaction

    {"next_block.block_num()":2389738}
    th_a  db_block.cpp:662 _apply_block

    {"new_block":{"previous":"002476e93f06fedf9ccd145e2606a0d5924a877b","timestamp":"2019-01-16T18:37:51","witness":"1.6.20","next_secret_hash":"67cba903a3e74f4cd2547cac43c0ae39ac17991a","previous_secret":"9c1913c3e6bdac802747a9899203ec15814cc8fa","transaction_merkle_root":"abe04fb2625ee68c0e21f0c1b4c9090c758c8b4a","extensions":[],"witness_signature":"205003e101e5d3f4ebc0828df5ffc2d527c1c0e397e78200e697703a35edfde16f5c8a058ed18f197408162a1484cf71719bb42864c034156db57ff1610079ca76","transactions":[{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"],"operation_results":[[1,"1.26.0"]]}]}}
    th_a  db_block.cpp:285 _push_block
998916ms th_a       fork_database.cpp:66          push_block           ] Pushing block to fork database that failed to link: 002476eb6b4d6273d517fffb48e716342261a5d9, 2389739
998916ms th_a       fork_database.cpp:67          push_block           ] Head: 2389738, 002476ea40838756a946f63ba77ed16644579355
998916ms th_a       application.cpp:528           handle_block         ] Error when pushing block:
3080000 unlinkable_block_exception: unlinkable block
block does not link to known chain
    {}
    th_a  fork_database.cpp:87 _push_block

    {"new_block":{"previous":"002476ea40838756a946f63ba77ed16644579355","timestamp":"2019-01-16T18:37:54","witness":"1.6.22","next_secret_hash":"935fc930d4ef923dd7d0cb8c350817f61ed8085a","previous_secret":"be16354beffdb8b6221f60d7627607c626c2b9dc","transaction_merkle_root":"0000000000000000000000000000000000000000","extensions":[],"witness_signature":"1f50b85c15de2902e1804d130cc854816c75d88b569a44d766e0c293fa1e3d3a5d36bb5fd9902833061ea606f3d74a8907520756df25e4351c4281c7f5e8351c17","transactions":[]}}
    th_a  db_block.cpp:285 _push_block
998920ms th_a       fork_database.cpp:66          push_block           ] Pushing block to fork database that failed to link: 002476ec30ae8902069fab570883a8770a186db4, 2389740
998920ms th_a       fork_database.cpp:67          push_block           ] Head: 2389738, 002476ea40838756a946f63ba77ed16644579355
998920ms th_a       application.cpp:528           handle_block         ] Error when pushing block:
3080000 unlinkable_block_exception: unlinkable block
block does not link to known chain
    {}
    th_a  fork_database.cpp:87 _push_block

    {"new_block":{"previous":"002476eb6b4d6273d517fffb48e716342261a5d9","timestamp":"2019-01-16T18:37:57","witness":"1.6.17","next_secret_hash":"6def0d23f26a9c58e5d4b5bb2e81e035f0538d96","previous_secret":"fc7efcb02ca526e9208cafcb6c16d97aeda0a2ef","transaction_merkle_root":"0000000000000000000000000000000000000000","extensions":[],"witness_signature":"1f7731d250e0c4cc1bb7767d9372b7abf6799c89f3d23b4a8c8b9606d7b85aeec7389f063ee6df2b3f73ff26e32b7d8a2c97458896134b2b569f298b825c282057","transactions":[]}}
    th_a  db_block.cpp:285 _push_block
1010884ms th_a       db_block.cpp:279              _push_block          ] Failed to push new block:
10 assert_exception: Assert Exception
maybe_found != nullptr: Unable to find Object
    {"id":"1.25.224"}
    th_a  index.hpp:113 get

    {"op":{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}}
    th_a  betting_market_evaluator.cpp:312 do_evaluate

    {}
    th_a  evaluator.cpp:51 start_evaluate

    {"op":[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]}
    th_a  db_block.cpp:780 apply_operation

    {"trx":{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"]}}
    th_a  db_block.cpp:766 _apply_transaction

    {"next_block.block_num()":2389738}
    th_a  db_block.cpp:662 _apply_block
1010885ms th_a       application.cpp:531           handle_block         ] Error when pushing block:
10 assert_exception: Assert Exception
maybe_found != nullptr: Unable to find Object
    {"id":"1.25.224"}
    th_a  index.hpp:113 get

    {"op":{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}}
    th_a  betting_market_evaluator.cpp:312 do_evaluate

    {}
    th_a  evaluator.cpp:51 start_evaluate

    {"op":[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]}
    th_a  db_block.cpp:780 apply_operation

    {"trx":{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"]}}
    th_a  db_block.cpp:766 _apply_transaction

    {"next_block.block_num()":2389738}
    th_a  db_block.cpp:662 _apply_block

    {"new_block":{"previous":"002476e93f06fedf9ccd145e2606a0d5924a877b","timestamp":"2019-01-16T18:37:51","witness":"1.6.20","next_secret_hash":"67cba903a3e74f4cd2547cac43c0ae39ac17991a","previous_secret":"9c1913c3e6bdac802747a9899203ec15814cc8fa","transaction_merkle_root":"abe04fb2625ee68c0e21f0c1b4c9090c758c8b4a","extensions":[],"witness_signature":"205003e101e5d3f4ebc0828df5ffc2d527c1c0e397e78200e697703a35edfde16f5c8a058ed18f197408162a1484cf71719bb42864c034156db57ff1610079ca76","transactions":[{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"],"operation_results":[[1,"1.26.0"]]}]}}
    th_a  db_block.cpp:285 _push_block
1010885ms th_a       fork_database.cpp:66          push_block           ] Pushing block to fork database that failed to link: 002476eb6b4d6273d517fffb48e716342261a5d9, 2389739
1010885ms th_a       fork_database.cpp:67          push_block           ] Head: 2389738, 002476ea40838756a946f63ba77ed16644579355
1010885ms th_a       application.cpp:528           handle_block         ] Error when pushing block:
3080000 unlinkable_block_exception: unlinkable block
block does not link to known chain
    {}
    th_a  fork_database.cpp:87 _push_block

    {"new_block":{"previous":"002476ea40838756a946f63ba77ed16644579355","timestamp":"2019-01-16T18:37:54","witness":"1.6.22","next_secret_hash":"935fc930d4ef923dd7d0cb8c350817f61ed8085a","previous_secret":"be16354beffdb8b6221f60d7627607c626c2b9dc","transaction_merkle_root":"0000000000000000000000000000000000000000","extensions":[],"witness_signature":"1f50b85c15de2902e1804d130cc854816c75d88b569a44d766e0c293fa1e3d3a5d36bb5fd9902833061ea606f3d74a8907520756df25e4351c4281c7f5e8351c17","transactions":[]}}
    th_a  db_block.cpp:285 _push_block
1021963ms th_a       db_block.cpp:279              _push_block          ] Failed to push new block:
10 assert_exception: Assert Exception
maybe_found != nullptr: Unable to find Object
    {"id":"1.25.224"}
    th_a  index.hpp:113 get

    {"op":{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}}
    th_a  betting_market_evaluator.cpp:312 do_evaluate

    {}
    th_a  evaluator.cpp:51 start_evaluate

    {"op":[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]}
    th_a  db_block.cpp:780 apply_operation

    {"trx":{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"]}}
    th_a  db_block.cpp:766 _apply_transaction

    {"next_block.block_num()":2389738}
    th_a  db_block.cpp:662 _apply_block
1021963ms th_a       application.cpp:531           handle_block         ] Error when pushing block:
10 assert_exception: Assert Exception
maybe_found != nullptr: Unable to find Object
    {"id":"1.25.224"}
    th_a  index.hpp:113 get

    {"op":{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}}
    th_a  betting_market_evaluator.cpp:312 do_evaluate

    {}
    th_a  evaluator.cpp:51 start_evaluate

    {"op":[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]}
    th_a  db_block.cpp:780 apply_operation

    {"trx":{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"]}}
    th_a  db_block.cpp:766 _apply_transaction

    {"next_block.block_num()":2389738}
    th_a  db_block.cpp:662 _apply_block

    {"new_block":{"previous":"002476e93f06fedf9ccd145e2606a0d5924a877b","timestamp":"2019-01-16T18:37:51","witness":"1.6.20","next_secret_hash":"67cba903a3e74f4cd2547cac43c0ae39ac17991a","previous_secret":"9c1913c3e6bdac802747a9899203ec15814cc8fa","transaction_merkle_root":"abe04fb2625ee68c0e21f0c1b4c9090c758c8b4a","extensions":[],"witness_signature":"205003e101e5d3f4ebc0828df5ffc2d527c1c0e397e78200e697703a35edfde16f5c8a058ed18f197408162a1484cf71719bb42864c034156db57ff1610079ca76","transactions":[{"ref_block_num":30440,"ref_block_prefix":1966282209,"expiration":"2019-01-16T18:38:03","operations":[[62,{"fee":{"amount":100000,"asset_id":"1.3.0"},"bettor_id":"1.2.50","betting_market_id":"1.25.224","amount_to_bet":{"amount":100000,"asset_id":"1.3.1"},"backer_multiplier":10100,"back_or_lay":"back","extensions":[]}]],"extensions":[],"signatures":["2001354580aa5fe2e9282d7c0ac71464c6570e4f0de86b09d2bd2d722252a71ed332542d83a26dd6b44f05a87b4623b743d0b227f429362dbc5837174b6930ca5c"],"operation_results":[[1,"1.26.0"]]}]}}
    th_a  db_block.cpp:285 _push_block
1022074ms th_a       fork_database.cpp:66          push_block           ] Pushing block to fork database that failed to link: 002476eb6b4d6273d517fffb48e716342261a5d9, 2389739
1022074ms th_a       fork_database.cpp:67          push_block           ] Head: 2389738, 002476ea40838756a946f63ba77ed16644579355
1022074ms th_a       application.cpp:528           handle_block         ] Error when pushing block:
3080000 unlinkable_block_exception: unlinkable block
block does not link to known chain
    {}
    th_a  fork_database.cpp:87 _push_block

    {"new_block":{"previous":"002476ea40838756a946f63ba77ed16644579355","timestamp":"2019-01-16T18:37:54","witness":"1.6.22","next_secret_hash":"935fc930d4ef923dd7d0cb8c350817f61ed8085a","previous_secret":"be16354beffdb8b6221f60d7627607c626c2b9dc","transaction_merkle_root":"0000000000000000000000000000000000000000","extensions":[],"witness_signature":"1f50b85c15de2902e1804d130cc854816c75d88b569a44d766e0c293fa1e3d3a5d36bb5fd9902833061ea606f3d74a8907520756df25e4351c4281c7f5e8351c17","transactions":[]}}
    th_a  db_block.cpp:285 _push_block
1022074ms th_a       fork_database.cpp:66          push_block           ] Pushing block to fork database that failed to link: 002476ec30ae8902069fab570883a8770a186db4, 2389740
1022074ms th_a       fork_database.cpp:67          push_block           ] Head: 2389738, 002476ea40838756a946f63ba77ed16644579355
1022074ms th_a       application.cpp:528           handle_block         ] Error when pushing block:
3080000 unlinkable_block_exception: unlinkable block
block does not link to known chain
    {}
    th_a  fork_database.cpp:87 _push_block

    {"new_block":{"previous":"002476eb6b4d6273d517fffb48e716342261a5d9","timestamp":"2019-01-16T18:37:57","witness":"1.6.17","next_secret_hash":"6def0d23f26a9c58e5d4b5bb2e81e035f0538d96","previous_secret":"fc7efcb02ca526e9208cafcb6c16d97aeda0a2ef","transaction_merkle_root":"0000000000000000000000000000000000000000","extensions":[],"witness_signature":"1f7731d250e0c4cc1bb7767d9372b7abf6799c89f3d23b4a8c8b9606d7b85aeec7389f063ee6df2b3f73ff26e32b7d8a2c97458896134b2b569f298b825c282057","transactions":[]}}
    th_a  db_block.cpp:285 _push_block
1022074ms th_a       fork_database.cpp:66          push_block           ] Pushing block to fork database that failed to link: 002476ed5cd4ae738d74d4fa02481f8bf8a5265f, 2389741
1022074ms th_a       fork_database.cpp:67          push_block           ] Head: 2389738, 002476ea40838756a946f63ba77ed16644579355
1022074ms th_a       application.cpp:528           handle_block         ] Error when pushing block:

...
```
