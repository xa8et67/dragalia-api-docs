/summon/get_summon_list
============================================================

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

	{}

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
	        "summon_list": [
	            {
	                "summon_id": 1020203,
	                "summon_type": 2,
	                "single_crystal": 120,
	                "single_diamond": 120,
	                "multi_crystal": 1200,
	                "multi_diamond": 1200,
	                "limited_crystal": 0,
	                "limited_diamond": 30,
	                "summon_point_id": 1020203,
	                "add_summon_point": 1,
	                "add_summon_point_stone": 2,
	                "exchange_summon_point": 300,
	                "status": 1,
	                "commence_date": 1661752800,
	                "complete_date": 1662098399,
	                "daily_count": 0,
	                "daily_limit": 1,
	                "total_limit": 0,
	                "total_count": 0,
	                "campaign_type": 0,
	                "free_count_rest": 0,
	                "is_beginner_campaign": 1,
	                "beginner_campaign_count_rest": 1,
	                "consecution_campaign_count_rest": 0
	            }
	        ],
	        "campaign_summon_list": [],
	        "chara_ssr_summon_list": [],
	        "dragon_ssr_summon_list": [],
	        "chara_ssr_update_summon_list": [],
	        "dragon_ssr_update_summon_list": [],
	        "campaign_ssr_summon_list": [],
	        "platinum_summon_list": [],
	        "exclude_summon_list": [
	            {
	                "summon_id": 1110003,
	                "priority": 101136,
	                "summon_type": 11,
	                "single_crystal": 0,
	                "single_diamond": 0,
	                "multi_crystal": 0,
	                "multi_diamond": 1200,
	                "limited_crystal": 0,
	                "limited_diamond": 0,
	                "summon_point_id": 0,
	                "add_summon_point": 0,
	                "add_summon_point_stone": 0,
	                "exchange_summon_point": 0,
	                "status": 1,
	                "commence_date": 1661752800,
	                "complete_date": 1662098399,
	                "daily_count": 0,
	                "daily_limit": 0,
	                "total_limit": 2,
	                "total_count": 0,
	                "campaign_type": 0,
	                "free_count_rest": 0,
	                "is_beginner_campaign": 0,
	                "beginner_campaign_count_rest": 0,
	                "consecution_campaign_count_rest": 0
	            }
	        ],
	        "cs_summon_list": {
	            "summon_list": [],
	            "platinum_summon_list": [],
	            "campaign_summon_list": [],
	            "campaign_ssr_summon_list": [],
	            "exclude_summon_list": []
	        },
	        "summon_ticket_list": [
	            {
	                "key_id": 367919,
	                "summon_ticket_id": 10102,
	                "quantity": 1,
	                "use_limit_time": 0
	            }
	        ],
	        "summon_point_list": [],
	        "update_data_list": {
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------