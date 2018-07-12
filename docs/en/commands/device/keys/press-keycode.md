# Press Key Code

Press a particular key on the device
## Example Usage

```java
// Java
driver.pressKeyCode(AndroidKeyCode.SPACE, AndroidKeyMetastate.META_SHIFT_ON);

```

```python
# Python
self.driver.press_keycode(10);

```

```javascript
// Javascript
// webdriver.io example
driver.pressKeycode(10);



// wd example
await driver.pressKeycode(10);

```

```ruby
# Ruby
@driver.press_keycode(10)

```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
// TODO C# sample

```



## Support

### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | None | None | None |
| Android | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | None | None | None |

### Appium Clients

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All |  [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/windows/PressesKeyCode.html#pressKeyCode-int-)  |
|[Python](https://github.com/appium/python-client/releases/latest)| All |  [github.com](https://github.com/appium/python-client/blob/master/appium/webdriver/webdriver.py#L415)  |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  [webdriver.io](http://webdriver.io/api/mobile/longPressKeycode.html)  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All |  [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L2457)  |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All |  [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#press_keycode-instance_method)  |
|[PHP](https://github.com/appium/php-client/releases/latest)| All |  [github.com](https://github.com/appium/php-client/)  |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All |  [github.com](https://github.com/appium/appium-dotnet-driver/)  |

## HTTP API Specifications

### Endpoint

`POST /session/:session_id/appium/device/press_keycode`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to route the command to|

### JSON Parameters

|name|type|description|
|----|----|-----------|
| keycode | `number` | Key code pressed on the device. See [Key Event](http://developer.android.com/reference/android/view/KeyEvent.html). |
| metastate | `number` | Metastate for the keypress. See [Key Event](http://developer.android.com/reference/android/view/KeyEvent.html). |
| flags | `number` | Flags for the keypress. See [Key Event](http://developer.android.com/reference/android/view/KeyEvent.html). |

### Response

null

## See Also

<<<<<<< HEAD
<<<<<<< HEAD
* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L357)
=======
* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L328)
>>>>>>> e0f92e0b... Update move docs (#10734)
=======
* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L357)
>>>>>>> a9c6eb57... Dynamically figure out line numbers to routes file when necessary (#10742)