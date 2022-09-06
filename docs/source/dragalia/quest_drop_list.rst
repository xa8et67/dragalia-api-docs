/quest/drop_list
==================================================

- Base address: production-api.dragalialost.com/2.19.0_20220714193707
- Method: POST
- Status code: 200

Request headers
----------------

.. code-block:: text

	Host: production-api.dragalialost.com

Request body
----------------

.. code-block:: json

	{
	    "quest_id": 201010104
	}

Response headers
----------------

.. code-block:: text

	Content-Type: application/x-msgpack

Response
----------------

.. code-block:: json

	{
	    "data_headers": {
	        "result_code": 1
	    },
	    "data": {
	        "quest_drop_info": {
	            "drop_info_list": [
	                {
	                    "entity_type": 8,
	                    "entity_id": 101001003
	                },
	                {
	                    "entity_type": 8,
	                    "entity_id": 103001003
	                },
	                {
	                    "entity_type": 8,
	                    "entity_id": 102001003
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030004
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030005
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030006
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030013
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030014
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030015
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030023
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030026
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030018
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030034
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40030036
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40040002
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40040014
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40040034
	                },
	                {
	                    "entity_type": 39,
	                    "entity_id": 40050002
	                },
	                {
	                    "entity_type": 26,
	                    "entity_id": 10101
	                }
	            ],
	            "host_drop_info_list": [],
	            "fever_drop_info_list": [],
	            "quest_bonus_info_list": [
	                {
	                    "entity_type": 8,
	                    "entity_id": 101001003
	                },
	                {
	                    "entity_type": 18,
	                    "entity_id": 0
	                }
	            ],
	            "quest_reborn_bonus_info_list": [],
	            "campaign_extra_reward_info_list": []
	        },
	        "update_data_list": {
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------