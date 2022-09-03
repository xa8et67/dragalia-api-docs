/dmode_dungeon/restart
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
	        "dmode_dungeon_state": 7,
	        "dmode_dungeon_info": {
	            "chara_id": 10230501,
	            "floor_num": 2,
	            "quest_time": 57,
	            "dungeon_score": 1400,
	            "is_play_end": 0,
	            "state": 7
	        },
	        "dmode_ingame_data": {
	            "recovery_count": 1,
	            "recovery_time": 1662162807,
	            "unique_key": "66709573935_1662162703",
	            "start_floor_num": 1,
	            "target_floor_num": 60,
	            "dmode_level_group_id": 1,
	            "unit_data": {
	                "chara_id": 10230501,
	                "dmode_chara_level_group_id": 1,
	                "skill_1_level": 3,
	                "skill_2_level": 2,
	                "ability_1_level": 2,
	                "ability_2_level": 2,
	                "ability_3_level": 1,
	                "ex_ability_level": 5,
	                "ex_ability_2_level": 5,
	                "burst_attack_level": 2,
	                "combo_buildup_count": 0
	            },
	            "servitor_id": 2,
	            "dmode_servitor_passive_list": []
	        },
	        "update_data_list": {
	            "dmode_info": {
	                "total_max_floor_num": 0,
	                "recovery_count": 1,
	                "recovery_time": 1662162807,
	                "floor_skip_count": 0,
	                "floor_skip_time": 0,
	                "dmode_point_1": 0,
	                "dmode_point_2": 0,
	                "is_entry": 1
	            },
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------