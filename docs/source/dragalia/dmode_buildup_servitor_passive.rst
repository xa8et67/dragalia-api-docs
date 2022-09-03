/dmode/buildup_servitor_passive
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
	    "request_buildup_passive_list": [
	        {
	            "passive_no": 2,
	            "passive_level": 19
	        }
	    ]
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
	        "dmode_servitor_passive_list": [
	            {
	                "passive_no": 1,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 2,
	                "passive_level": 19
	            },
	            {
	                "passive_no": 3,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 4,
	                "passive_level": 12
	            },
	            {
	                "passive_no": 5,
	                "passive_level": 20
	            },
	            {
	                "passive_no": 6,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 7,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 8,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 9,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 10,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 11,
	                "passive_level": 1
	            },
	            {
	                "passive_no": 12,
	                "passive_level": 1
	            },
	            {
	                "passive_no": 13,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 14,
	                "passive_level": 10
	            },
	            {
	                "passive_no": 15,
	                "passive_level": 1
	            },
	            {
	                "passive_no": 16,
	                "passive_level": 1
	            },
	            {
	                "passive_no": 17,
	                "passive_level": 1
	            }
	        ],
	        "update_data_list": {
	            "dmode_info": {
	                "total_max_floor_num": 60,
	                "recovery_count": 3,
	                "recovery_time": 1653360289,
	                "floor_skip_count": 1,
	                "floor_skip_time": 1653243974,
	                "dmode_point_1": 287,
	                "dmode_point_2": 703,
	                "is_entry": 1
	            },
	            "functional_maintenance_list": []
	        },
	        "entity_result": {
	            "converted_entity_list": []
	        }
	    }
	}

Notes
------