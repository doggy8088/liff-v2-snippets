# LIFF Snippets

The **LIFF v2** ([LINE Front-end Framework](https://developers.line.biz/en/docs/liff/overview/)) Code Snippets. It supports most of the APIs in [LIFF v2 API reference](https://developers.line.biz/en/reference/liff/). Type definitions for TypeScript are already included in the [@line/liff](https://www.npmjs.com/package/@line/liff) package.

## Snippets Included

This extension contains a set of LIFF v2 code snippets that helps LIFF app developers write code faster.

### HTML snippets

* `liffsdk`: Put LIFF v2 SDK to the beginning of the BODY tag.

### TypeScript/JavaScript snippets

* LIFF SDK properties

  * `liff-ready`

      A property holding the Promise object that resolves when you run liff.init() for the first time after starting the LIFF app.

* Initialization

  * `liff-import` or `import-liff`

      Import [@line/liff](https://www.npmjs.com/package/@line/liff) module

  * `liff-init`

      Initializes a LIFF app.

* Getting environment

  * `liff-getContext`

      Gets the screen type (`1-on-1 chat`, `group chat`, `multi-person chat`, or `external browser`) from which the LIFF app is launched. For `1-on-1 chats`, `group chats`, and `multi-person chats`, you also get a **unique ID**.

  * `liff-isInClient`

      Determines whether the LIFF app is running in a LIFF browser.

  * `liff-isApiAvailable`

      Checks whether the specified API is available in the environment where you started the LIFF app.

  * `liff-isApiAvailable-shareTargetPicker`

      liff.isApiAvailable('shareTargetPicker')

  * `liff-isApiAvailable-multipleLiffTransition`

      liff.isApiAvailable('multipleLiffTransition')

* Authentication

  * `liff-permission-query`

      Verifies whether the user agrees to grant the specified permission.

* Profile

  * `liff-getProfile`

      Gets the current user's profile information.

  * `liff-getFriendship`

      Gets the friendship status between a user and a LINE Official Account.

* Window

  * `liff-openWindow`

      Opens the specified URL in the LINE's in-app browser or external browser.

  * `liff-closeWindow`

      Closes the LIFF app.

* Message

  * `liff-sendMessages`

      Sends messages on behalf of the user to the chat screen where the LIFF app is opened. This feature is only available in a LIFF app launched from a one-on-one chat room.

  * `liff-liff-shareTargetPicker`

      Displays the target picker (screen for selecting a group or friend) and sends the message created by the developer to the selected target. This message appears to your group or friends as if you had sent it.

  * `liff-msg-text`

      Represent a `TEXT` message object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-image`

      Represent an `IMAGE` message object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-location`

      Represent a `LOCATION` message object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-sticker`

      Represent a `STICKER` message object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-video`

      Represent a `VIDEO` message object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-audio`

      Represent an `AUDIO` message object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-flex`

      Represent a `Flex Message` object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-Template-Buttons`

      Represent a `Template Messages (Buttons)` object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-Template-Confirm`

      Represent a `Template Messages (Confirm)` object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-Template-Carousel`

      Represent a `Template Messages (Carousel)` object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

  * `liff-msg-Template-ImageCarousel`

      Represent a `Template Messages (Image Carousel)` object used in `liff.sendMessages()` or `liff.shareTargetPicker()` API.

* Camera

  * `liff-scanCodeV2`

      Launch the 2D code reader and obtain string. To activate the 2D code reader, turn on Scan QR on the LINE Developers Console.

* Permanent link

  * `liff-permanentLink-createUrlBy`

      Get the permanent link of any page in the LIFF app.

### Links

* [LINE Front-end Framework](https://developers.line.biz/en/docs/liff/overview/)
* [Developing a LIFF app](https://developers.line.biz/en/docs/liff/developing-liff-apps/)
* [LIFF v2 API reference](https://developers.line.biz/en/reference/liff/)
* [LIFF Release notes](https://developers.line.biz/en/docs/liff/release-notes/)
* [LIFF Versioning policy](https://developers.line.biz/en/docs/liff/versioning-policy/)

**Enjoy!**
