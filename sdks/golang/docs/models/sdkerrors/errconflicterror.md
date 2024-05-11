# ErrConflictError


## Fields

| Field                                                                  | Type                                                                   | Required                                                               | Description                                                            | Example                                                                |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `Code`                                                                 | [sdkerrors.ErrConflictCode](../../models/sdkerrors/errconflictcode.md) | :heavy_check_mark:                                                     | A machine readable error code.                                         | CONFLICT                                                               |
| `Docs`                                                                 | *string*                                                               | :heavy_check_mark:                                                     | A link to our documentation with more details about this error code    | https://unkey.dev/docs/api-reference/errors/code/CONFLICT              |
| `Message`                                                              | *string*                                                               | :heavy_check_mark:                                                     | A human readable explanation of what went wrong                        |                                                                        |
| `RequestID`                                                            | *string*                                                               | :heavy_check_mark:                                                     | Please always include the requestId in your error report               | req_1234                                                               |