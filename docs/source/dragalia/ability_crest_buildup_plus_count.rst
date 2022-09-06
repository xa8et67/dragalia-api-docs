/ability_crest/buildup_plus_count
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
	    "ability_crest_id": 40050010,
	    "plus_count_params_list": [
	        {
	            "plus_count_type": 1,
	            "plus_count": 50
	        },
	        {
	            "plus_count_type": 2,
	            "plus_count": 50
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
	        "update_data_list": {
	            "ability_crest_list": [
	                {
	                    "ability_crest_id": 40050010,
	                    "buildup_count": 0,
	                    "limit_break_count": 0,
	                    "equipable_count": 1,
	                    "hp_plus_count": 50,
	                    "attack_plus_count": 50,
	                    "is_new": 1,
	                    "is_favorite": 0,
	                    "gettime": 1601459403
	                }
	            ],
	            "material_list": [
	                {
	                    "material_id": 122001001,
	                    "quantity": 3542
	                },
	                {
	                    "material_id": 123001001,
	                    "quantity": 3818
	                }
	            ],
	            "functional_maintenance_list": []
	        },
	        "entity_result": {
	            "converted_entity_list": []
	        }
	    }
	}

Notes
------