/friend/set_support_chara
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

	{
	    "chara_id": 10130103,
	    "dragon_key_id": 0,
	    "weapon_key_id": 0,
	    "amulet_key_id": 0,
	    "amulet_2_key_id": 0,
	    "weapon_body_id": 0,
	    "crest_slot_type_1_crest_id_1": 0,
	    "crest_slot_type_1_crest_id_2": 0,
	    "crest_slot_type_1_crest_id_3": 0,
	    "crest_slot_type_2_crest_id_1": 0,
	    "crest_slot_type_2_crest_id_2": 0,
	    "crest_slot_type_3_crest_id_1": 0,
	    "crest_slot_type_3_crest_id_2": 0,
	    "talisman_key_id": 0
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
	        "result": 1,
	        "setting_support": {
	            "last_active_time": 1661984335,
	            "chara_id": 10130103,
	            "equip_dragon_key_id": 0,
	            "equip_weapon_body_id": 0,
	            "equip_crest_slot_type_1_crest_id_1": 0,
	            "equip_crest_slot_type_1_crest_id_2": 0,
	            "equip_crest_slot_type_1_crest_id_3": 0,
	            "equip_crest_slot_type_2_crest_id_1": 0,
	            "equip_crest_slot_type_2_crest_id_2": 0,
	            "equip_crest_slot_type_3_crest_id_1": 0,
	            "equip_crest_slot_type_3_crest_id_2": 0,
	            "equip_talisman_key_id": 0,
	            "user_level_group": 0
	        },
	        "update_data_list": {
	            "mission_notice": {
	                "normal_mission_notice": {
	                    "is_update": 1,
	                    "receivable_reward_count": 1,
	                    "new_complete_mission_id_list": [
	                        10005101
	                    ],
	                    "pickup_mission_count": 0,
	                    "all_mission_count": 222,
	                    "completed_mission_count": 5,
	                    "current_mission_id": 0
	                },
	                "daily_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "period_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "beginner_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "special_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "main_story_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "memory_event_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "drill_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                },
	                "album_mission_notice": {
	                    "is_update": 0,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0
	                }
	            },
	            "current_main_story_mission": [],
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------