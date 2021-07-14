# FlashChat
## What We Will Create

We’re going to make a Flash Chat App, where you can register or login on a device/simulator and then you will be able to type a message and "chat" with someone, aka you on a different device/simulator.

## What You'll Learn

You will learn about Segues, For Loops, Installing Cocoapods & Other Alternatives, Adding & Using Firebase, and much more. 

# Constants
```
struct K {
    static let appName = "⚡️FlashChat"
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

```

>This is a project from the iCodeLife iOS 15 & Swift Course, check out the full course at [www.icodelife.com/courses](https://www.icodelife.com/courses)
