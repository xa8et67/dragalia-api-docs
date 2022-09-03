/guild/update_guild_position_type
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
	    "guild_id": 72987015,
	    "target_viewer_id": 71560925622,
	    "guild_position_type": 2
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
	        "guild_member_list": [
	            {
	                "viewer_id": 71560925622,
	                "user_name": "Ephraim",
	                "user_level": 120,
	                "max_party_power": 30346,
	                "profile_entity_type": 1,
	                "profile_entity_id": 10250102,
	                "profile_entity_rarity": 5,
	                "last_active_time": 1652863746,
	                "last_guild_active_time": 0,
	                "last_attend_time": 1651654155,
	                "guild_position_type": 2,
	                "temporary_end_time": 0
	            },
	            {
	                "viewer_id": 97571459880,
	                "user_name": "Jay",
	                "user_level": 174,
	                "max_party_power": 52604,
	                "profile_entity_type": 1,
	                "profile_entity_id": 10150303,
	                "profile_entity_rarity": 5,
	                "last_active_time": 1662205461,
	                "last_guild_active_time": 1662205493,
	                "last_attend_time": 1662205478,
	                "guild_position_type": 1,
	                "temporary_end_time": 0
	            }
	        ],
	        "update_data_list": {
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------