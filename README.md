# Lovat_Api

## Description
WordPress WooCommerce REST API Lovat Api

## Installing the plugin

Download the extension as a ZIP file from this repository in the directory wp-content/plugins

Next, activate the plugin and get the access key in the settings.

Use request authorization

```
Authorization: Bearer Token
```
Arguments `from` `to` `p`

`from` `to` -> date format

`p` -> integer (pagination), default = 1

Request URL
```
/wp-json/v1/orders?from=date&to=date&p=integer
```
 
Example request URL

```
http://localhost/wp-json/v1/orders?from=15.08.2020&to=30.08.2020&p=1
```

The search is performed on such statuses as `completed` and ` refunded`
