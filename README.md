# LIFF Snippets

The **LIFF v2** ([LINE Front-end Framework](https://developers.line.biz/en/docs/liff/overview/)) Code Snippets. It supports most of the APIs in [LIFF v2 API reference](https://developers.line.biz/en/reference/liff/). Type definitions for TypeScript are already included in the [@line/liff](https://www.npmjs.com/package/@line/liff) package.

## Snippets Included

This extension contains a set of LIFF v2 code snippets that helps LIFF app developers write code faster.

### HTML snippets

* `liffsdk`: Insert LIFF v2 SDK into HTML.

### TypeScript/JavaScript snippets

| snippet                                      | description                                                                                                                                                                                                     |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `liff-import`                                | Import [@line/liff](https://www.npmjs.com/package/@line/liff) module                                                                                                                                            |
| `liff-init`                                  | Initializes a LIFF app.                                                                                                                                                                                         |
| `liff-ready`                                 | A property holding the Promise object that resolves when you run liff.init() for the first time after starting the LIFF app.                                                                                    |
| `liff-isInClient`                            | Determines whether the LIFF app is running in a LIFF browser.                                                                                                                                                   |
| `liff-isApiAvailable`                        | Checks whether the specified API is available in the environment where you started the LIFF app.                                                                                                                |
| `liff-isApiAvailable-shareTargetPicker`      | liff.isApiAvailable('shareTargetPicker')                                                                                                                                                                        |
| `liff-isApiAvailable-multipleLiffTransition` | liff.isApiAvailable('multipleLiffTransition')                                                                                                                                                                   |
| `liff-permission-query`                      | Verifies whether the user agrees to grant the specified permission.                                                                                                                                             |
| `liff-getProfile`                            | Gets the current user's profile information.                                                                                                                                                                    |
| `liff-getFriendship`                         | Gets the friendship status between a user and a LINE Official Account.                                                                                                                                          |
| `liff-openWindow`                            | Opens the specified URL in the LINE's in-app browser or external browser.                                                                                                                                       |
| `liff-closeWindow`                           | Closes the LIFF app.                                                                                                                                                                                            |
| `liff-sendMessages`                          | Sends TEXT messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                                   |
| `liff-sendMessages-image`                    | Sends IMAGE messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                                  |
| `liff-sendMessages-location`                 | Sends LOCATION messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                               |
| `liff-sendMessages-sticker`                  | Sends STICKER messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                                |
| `liff-sendMessages-video`                    | Sends VIDEO messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                                  |
| `liff-sendMessages-audio`                    | Sends AUDIO messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                                  |
| `liff-sendMessages-flex`                     | Sends Flex Messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                                   |
| `liff-sendMessages-Template-Buttons`         | Sends Template Messages (Buttons) on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                     |
| `liff-sendMessages-Template-Confirm`         | Sends Template Messages (Confirm) on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                     |
| `liff-sendMessages-Template-Carousel`        | Sends Template Messages (Carousel) on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.                    |
| `liff-sendMessages-Template-ImageCarousel`   | Sends Template Messages (Image Carousel) on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.              |
| `liff-liff-shareTargetPicker`                | Displays the target picker (screen for selecting a group or friend) and sends the message created by the developer to the selected target. This message appears to your group or friends as if you had sent it. |
| `liff-scanCodeV2`                            | Launch the 2D code reader and obtain string. To activate the 2D code reader, turn on Scan QR on the LINE Developers Console.                                                                                    |
| `liff-permanentLink-createUrlBy`             | Get the permanent link of any page in the LIFF app.                                                                                                                                                             |

### Links

* [LINE Front-end Framework](https://developers.line.biz/en/docs/liff/overview/)
* [Developing a LIFF app](https://developers.line.biz/en/docs/liff/developing-liff-apps/)
* [LIFF v2 API reference](https://developers.line.biz/en/reference/liff/)
* [LIFF Release notes](https://developers.line.biz/en/docs/liff/release-notes/)
* [LIFF Versioning policy](https://developers.line.biz/en/docs/liff/versioning-policy/)

**Enjoy!**
