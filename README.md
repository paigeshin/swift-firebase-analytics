# swift-firebase-analytics

```swift
import FirebaseAnalyticsSwift
import SwiftUI

extension View {

    func track(_ screen: String) -> some View {
        self
            .analyticsScreen(name: screen)
    }
    
}

```
