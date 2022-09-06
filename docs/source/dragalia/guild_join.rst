/guild/join
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
	    "guild_id": 87745518
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
	                "viewer_id": 28894575482,
	                "user_name": "Euden",
	                "user_level": 60,
	                "max_party_power": 5738,
	                "profile_entity_type": 1,
	                "profile_entity_id": 10140101,
	                "profile_entity_rarity": 4,
	                "last_active_time": 1662300744,
	                "last_guild_active_time": 1662301841,
	                "last_attend_time": 0,
	                "guild_position_type": 3,
	                "temporary_end_time": 0
	            },
	            {
	                "viewer_id": 30305325753,
	                "user_name": "Sturmy",
	                "user_level": 23,
	                "max_party_power": 9632,
	                "profile_entity_type": 1,
	                "profile_entity_id": 10140101,
	                "profile_entity_rarity": 5,
	                "last_active_time": 1566625250,
	                "last_guild_active_time": 0,
	                "last_attend_time": 1565592941,
	                "guild_position_type": 1,
	                "temporary_end_time": 0
	            }
	        ],
	        "update_data_list": {
	            "user_guild_data": {
	                "guild_id": 87745518,
	                "guild_apply_id": 0,
	                "penalty_end_time": 0,
	                "guild_push_notification_type_running": 1,
	                "guild_push_notification_type_suspending": 1,
	                "profile_entity_type": 1,
	                "profile_entity_id": 10140101,
	                "profile_entity_rarity": 4,
	                "last_attend_time": 0,
	                "is_enable_invite_receive": 1,
	                "is_enable_invite_send": 0
	            },
	            "guild_data": {
	                "guild_id": 87745518,
	                "guild_name": "Pendragon",
	                "guild_emblem_id": 10008,
	                "guild_introduction": "role-play is important, but real life always comes first.",
	                "joining_condition_type": 1,
	                "activity_policy_type": 3,
	                "is_penalty_guild_name": 0,
	                "is_penalty_guild_introduction": 0,
	                "guild_member_count": 2,
	                "guild_board": "Let's seize the day!",
	                "is_penalty_guild_board": 0
	            },
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------