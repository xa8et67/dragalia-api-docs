/friend/reply
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
	    "friend_id": 55169104656,
	    "reply": 1
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
	            "friend_notice": {
	                "friend_new_count": 2,
	                "apply_new_count": 0
	            },
	            "functional_maintenance_list": []
	        }
	    }
	}

Notes
------