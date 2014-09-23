
| Parameter           | Type    | Description                                     |
|:--------------------|:--------|:------------------------------------------------|
| email               | String  | Email linked to subscription.                   |
| subscription_number | String  | Subscription number to get subscriper data for. |
| override_sanitizer  | Bool    | Ignore this parameter. Sanitizer is enabled by default and it adjusts the output to return a true or false rather than the complete set of unprocessed data. Best practise is to ignore this param. It is only included for backwards compability. |

### Request body(s)
```json
{
  "email":"foo@foo.bar"
}

