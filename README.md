# Craftnet API Collection

An API collection for the [Bruno](https://www.usebruno.com/) client.

## Usage

Variables are set in the `environment` environment.

Optional string variables can either be set to `null` or a string including quotes, for example: `"2020-04-25T17:17:23+00:00"`. 

### `plugin-licenses/get`

Set the following environment variables:

- `license_key`

### `plugin-licenses/save`

Set the following environment variables:

- `license_key`
- `plugin_edition`
- `plugin_expirable`
- `plugin_expires_on` (Optional)
- `plugin_notes` (Optional)
- `plugin_private_notes` (Optional)

### `plugin-licenses/create`

Set the following environment variables:

- `plugin_handle`
- `plugin_edition`
- `plugin_licensee_email`
- `plugin_expirable`
- `plugin_expires_on` (Optional)
- `plugin_notes` (Optional)
- `plugin_private_notes` (Optional)
