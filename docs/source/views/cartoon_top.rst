/cartoon/top/
==================================================

- Base address: production-api.dragalialost.com
- Method: GET
- Status code: 200

Request headers
----------------

.. code-block:: text

	user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:104.0) Gecko/20100101 Firefox/104.0

Request body
----------------

.. code-block:: json

	null

Response headers
----------------

.. code-block:: text

	content-type: application/json

Response
----------------

.. code-block:: json

	{
	    "data_headers": {
	        "result_code": 1
	    },
	    "data": {
	        "top": {
	            "id_1st": 9,
	            "id": 1916,
	            "episode": 468,
	            "title": "That's a Wrap!",
	            "image": "https://dragalialost.akamaized.net/attached/cartoon/images/bafb6a3cd4b9207ae60e67ee5b4d2801.png"
	        },
	        "text_list": [
	            {
	                "message_id": "back_to_comic_list",
	                "text": "View All",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "comic_banner",
	                "text": "https://dragalialost.akamaized.net/static/image/comic/localized/en_us/banner_top_comic_01_webview.png",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "comic_episode_format",
	                "text": "#%s",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "comic_help_link_image",
	                "text": "https://dragalialost.akamaized.net/static/image/comic/localized/en_us/btn_helpcomic_01.png\t",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "comic_link_image_plotsynopsis",
	                "text": "https://dragalialost.akamaized.net/static/image/comic/localized/en_us/btn_comic_01.png",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "comic_update_info",
	                "text": "#%s added!",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "comic_update_info_accent",
	                "text": "#%s added!",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "plotsynopsis_banner",
	                "text": "https://dragalialost.akamaized.net/static/image/comic/localized/en_us/banner_top_plotsynopsis_01_webview.png\t",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "read_from_first_episode",
	                "text": "Start from #1",
	                "function_name": "comic"
	            },
	            {
	                "message_id": "to_comic_help",
	                "text": "Need help? Start here!",
	                "function_name": "comic"
	            }
	        ]
	    }
	}

Notes
------