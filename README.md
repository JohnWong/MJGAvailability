# MJGAvailability
Help checking iOS API availability. 帮助检查iOS API的可用性。来自[https://github.com/mattjgalloway](https://github.com/mattjgalloway/MJGFoundation/blob/master/Source/Utilities/MJGAvailability.h)

## Usage

For example, minimum version supported  of your app is iOS 7. In YourProjectPrefixHeader.pch:
```
#ifdef DEBUG
#define __IPHONE_OS_VERSION_SOFT_MAX_REQUIRED __IPHONE_7_0
#import "MJGAvailability.h"
#endif
```
