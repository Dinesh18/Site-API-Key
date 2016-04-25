# Site-API-Key

This module adds a new field "Site API Key" to site-information form (/admin/config/system/site-information.)
This module also provides a URL that responds with a JSON representation of a given node with the content type "page"
only if the previously submitted API Key and a node id (nid) of an appropriate node are present, otherwise it will respond with "access denied".
## Example URL

http://localhost/page_json/FOOBAR12345/17