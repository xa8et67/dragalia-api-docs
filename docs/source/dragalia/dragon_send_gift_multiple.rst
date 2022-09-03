/dragon/send_gift_multiple
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
	    "dragon_id": 20050419,
	    "dragon_gift_id": 30001,
	    "quantity": 1
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
	        "is_favorite": 0,
	        "return_gift_list": [
	            {
	                "entity_type": 8,
	                "entity_id": 201005001,
	                "entity_quantity": 2,
	                "is_over": 0
	            }
	        ],
	        "reward_reliability_list": [],
	        "update_data_list": {
	            "dragon_reliability_list": [
	                {
	                    "dragon_id": 20050419,
	                    "gettime": 1648381213,
	                    "reliability_level": 22,
	                    "reliability_total_exp": 17700,
	                    "last_contact_time": 1662206259
	                }
	            ],
	            "dragon_gift_list": [
	                {
	                    "dragon_gift_id": 30001,
	                    "quantity": 2
	                }
	            ],
	            "material_list": [
	                {
	                    "material_id": 201005001,
	                    "quantity": 8899
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