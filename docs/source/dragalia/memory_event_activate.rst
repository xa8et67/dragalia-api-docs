/memory_event/activate
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
	    "event_id": 20841
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
	        "update_data_list": {
	            "user_data": {
	                "viewer_id": 66709573935,
	                "name": "Eudenh",
	                "level": 4,
	                "exp": 640,
	                "crystal": 1719,
	                "coin": 2000417480,
	                "max_dragon_quantity": 160,
	                "max_weapon_quantity": 0,
	                "max_amulet_quantity": 0,
	                "quest_skip_point": 324,
	                "main_party_no": 6,
	                "emblem_id": 40000001,
	                "active_memory_event_id": 20841,
	                "mana_point": 44585,
	                "dew_point": 3170,
	                "build_time_point": 0,
	                "last_login_time": 1662158090,
	                "stamina_single": 232,
	                "last_stamina_single_update_time": 1662162035,
	                "stamina_single_surplus_second": 0,
	                "stamina_multi": 53,
	                "last_stamina_multi_update_time": 1662161791,
	                "stamina_multi_surplus_second": 0,
	                "tutorial_status": 20501,
	                "tutorial_flag_list": [
	                    1001,
	                    1002,
	                    1019,
	                    1020,
	                    1022,
	                    1023,
	                    1027
	                ],
	                "prologue_end_time": 1661979402,
	                "is_optin": 0,
	                "fort_open_time": 1662159858,
	                "create_time": 1661897736
	            },
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------