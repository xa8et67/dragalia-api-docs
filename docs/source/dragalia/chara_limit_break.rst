/chara/limit_break
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
	    "chara_id": 10950503,
	    "next_limit_break_count": 1,
	    "is_use_grow_material": 0
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
	        "update_data_list": {
	            "chara_list": [
	                {
	                    "chara_id": 10950503,
	                    "rarity": 5,
	                    "exp": 80500,
	                    "level": 36,
	                    "additional_max_level": 0,
	                    "hp_plus_count": 0,
	                    "attack_plus_count": 0,
	                    "limit_break_count": 1,
	                    "is_new": 1,
	                    "gettime": 1661976624,
	                    "skill_1_level": 1,
	                    "skill_2_level": 0,
	                    "ability_1_level": 1,
	                    "ability_2_level": 1,
	                    "ability_3_level": 0,
	                    "burst_attack_level": 1,
	                    "combo_buildup_count": 0,
	                    "hp": 287,
	                    "attack": 194,
	                    "ex_ability_level": 1,
	                    "ex_ability_2_level": 1,
	                    "is_temporary": 0,
	                    "is_unlock_edit_skill": 0,
	                    "mana_circle_piece_id_list": [
	                        1,
	                        2,
	                        3,
	                        4,
	                        5,
	                        6,
	                        7,
	                        8,
	                        9,
	                        10
	                    ],
	                    "list_view_flag": 1
	                }
	            ],
	            "material_list": [
	                {
	                    "material_id": 104001051,
	                    "quantity": 3
	                },
	                {
	                    "material_id": 104001052,
	                    "quantity": 0
	                }
	            ],
	            "mission_notice": {
	                "normal_mission_notice": {
	                    "is_update": 1,
	                    "receivable_reward_count": 2,
	                    "new_complete_mission_id_list": [
	                        10001001
	                    ],
	                    "pickup_mission_count": 0,
	                    "all_mission_count": 231,
	                    "completed_mission_count": 20,
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
	                    "is_update": 1,
	                    "receivable_reward_count": 0,
	                    "new_complete_mission_id_list": [],
	                    "pickup_mission_count": 0,
	                    "all_mission_count": 56,
	                    "completed_mission_count": 5,
	                    "current_mission_id": 0
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
	        },
	        "entity_result": {
	            "converted_entity_list": []
	        }
	    }
	}

Notes
------