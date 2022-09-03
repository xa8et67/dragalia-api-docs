/dragon/get_contact_data
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
	        "shop_gift_list": [
	            {
	                "dragon_gift_id": 10001,
	                "price": 0,
	                "is_buy": 1
	            },
	            {
	                "dragon_gift_id": 10002,
	                "price": 1500,
	                "is_buy": 1
	            },
	            {
	                "dragon_gift_id": 10003,
	                "price": 4000,
	                "is_buy": 1
	            },
	            {
	                "dragon_gift_id": 10004,
	                "price": 8000,
	                "is_buy": 1
	            },
	            {
	                "dragon_gift_id": 20005,
	                "price": 12000,
	                "is_buy": 1
	            }
	        ],
	        "update_data_list": {
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------