# whats360.live Postman Collection

Importable Postman collection for the [whats360.live WhatsApp API](https://github.com/whats360-api/whats360-api-docs): send messages, manage devices, run campaigns.

## Use
1. Import `whats360.postman_collection.json` and `whats360.postman_environment.json`.
2. In the environment set `api_key` (your token) and `device_id`. Leave them empty in anything you commit or share.
3. Variables: `{{base_url}}`, `{{api_key}}`, `{{device_id}}`, `{{campaign_id}}`, `{{jid}}`.
4. Run one text send to your own number first.

`disconnect` and `delete` change device state. Use a test device.

Status: built from the official reference, JSON validated, not run against production. The campaign recipients body is undocumented in the source.

Website: https://whats360.live · WhatsApp: https://wa.me/whats360.live · Direct chat support: https://wa.me/201030741766 · info@whats360.live
