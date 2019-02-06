# OfficeConfigs

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<aside class="success">
Remember — all requests are authenticated with JWT which sets the current user and office!
</aside>

## Get OfficeConfig

> JSON Response:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Max",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

This endpoint retrieves the OfficeConfig for the current Office.

### HTTP Request

`GET http://example.com/office_configs`

## Update OfficeConfig

> JSON Response (200)

```json
{
  "id": 2,
  "name": "Max",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

> JSON Response (404)

```json
false
```

This endpoint updates the OfficeConfig the current Office.

### HTTP Request

`PUT http://example.com/office_configs`

### Body Parameters

Parameter | Description
--------- | -----------
three_showing_choices | ...
group_showings | ...
multiple_calenders_switch | ...
one_renter_per_showing | ...
buffer_time | ...
confirmation_duration | ...
auto_cancel_duration | ...
assignment | ...
renter_per_showing | ...
one_property_per_day | ...
schedule_max_days | ...
slot_size | ...
start_slot | ...
end_slot | ...



