The `GiftWrapping` object can contain the following attributes.

Attribute |  Data Type | Description
--- | --- | ---
`design` | String! | The name of the gift wrapping design
`id` | ID! | Deprecated. Use `uid` instead. The unique identifier for the gift wrapping option
`image` | [GiftWrappingImage](#giftwrappingimage-object) | The preview image for the gift wrapping option
`price` | Money! | The price of the gift wrapping option
`uid` | ID! | The unique identifier for the `GiftWrapping` object

### GiftWrappingImage object

The `GiftWrappingImage` object must contain the following attributes.

Attribute |  Data Type | Description
--- | --- | ---
`label` | String! | The label of the gift wrapping preview image
`url` | String! | The URL of the gift wrapping preview image
